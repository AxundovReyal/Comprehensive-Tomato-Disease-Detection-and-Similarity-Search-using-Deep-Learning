# Comprehensive-Tomato-Disease-Detection-and-Similarity-Search-using-Deep-Learning
This project uses deep learning to detect and classify tomato leaf diseases and includes a similarity search to find visually similar cases. It aims to support agriculture by providing a fast, accurate tool for identifying tomato plant diseases.

🌿 Tomato Leaf Disease Detection using Deep Learning
This project focuses on building a deep learning model to detect and classify tomato leaf diseases using image data. The model is trained on the PlantVillage Tomato Disease Dataset, which contains thousands of labeled images of healthy and diseased tomato leaves.

📁 Dataset
Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)

Classes: The dataset includes multiple classes such as:

Tomato___Bacterial_spot

Tomato___Early_blight

Tomato___Late_blight

Tomato___Leaf_Mold

Tomato___Septoria_leaf_spot

Tomato___Spider_mites

Tomato___Target_Spot

Tomato___Tomato_Yellow_Leaf_Curl_Virus

Tomato___Tomato_mosaic_virus

Tomato___healthy

The dataset is preprocessed and augmented to improve model generalization.

🎯 Objective
The goal of this project is to:

Automatically detect tomato leaf diseases from images

Improve early disease diagnosis to support farmers

Integrate a similarity search module to retrieve visually similar disease samples based on feature embeddings

🛠 Technologies Used
Python, TensorFlow / Keras

Convolutional Neural Networks (CNNs)

OpenCV, NumPy, Matplotlib

Streamlit (for building the web interface)

📊 Model Performance
Evaluation metrics such as accuracy, precision, recall, and confusion matrix are used to assess the performance of the classification model.
