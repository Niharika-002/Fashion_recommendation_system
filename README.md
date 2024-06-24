# Fashion_recommendation_system

Welcome to the Fashion Recommendation System! This project leverages state-of-the-art transfer learning techniques and a K-Nearest Neighbors (KNN) model to provide personalized fashion recommendations by identifying similar images of clothing. This README will guide you through the setup, usage, and technical details of the system.

DATASET : 

# Table of Contents
1. Introduction
2. Features
3. Installation
4. Usage
5. Model Architecture
6. Result
7. License
8. Contact

# Introduction
The Fashion Recommendation System is designed to enhance the online shopping experience by suggesting clothing items similar to the ones users are interested in. By using transfer learning for feature extraction and a KNN model for similarity matching, the system provides accurate and efficient recommendations.

# Features
Transfer Learning: Utilizes pre-trained convolutional neural networks (CNNs) for feature extraction.
Similarity Matching: Implements K-Nearest Neighbors (KNN) to find and recommend similar clothing items.
Interactive Interface: Easy-to-use interface for uploading and receiving recommendations.   

# Installation
To set up the Fashion Recommendation System on your local machine, follow these steps:

1. Clone the repository:
   
   git clone https://github.com/your-username/fashion-recommendation-system.git
   cd fashion-recommendation-system


2. Create and activate a virtual environment:

   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`

4. Install dependencies:

   pip install -r requirements.txt

5. Run the application:

   python app.py

# Usage
Upload an image: Use the provided interface to upload an image of a clothing item.
Get Recommendations: The system will process the image and return a list of similar items.
Explore Results: View the recommended items and their details.

# Model Architecture
The Fashion Recommendation System employs the following architecture:

Transfer Learning: Uses a pre-trained CNN model (e.g., VGG16, ResNet50) to extract features from the input images.
Feature Extraction: The CNN model processes the images and outputs feature vectors.
KNN Model: These feature vectors are then fed into a KNN model to find and rank the most similar images in the dataset.

![image](https://github.com/Niharika-002/Fashion_recommendation_system/assets/111232798/aa8d09f8-d7ff-4845-9b9e-4dea1978fff6)

# Results
The system has demonstrated high accuracy in identifying and recommending similar clothing items. 


![image](https://github.com/Niharika-002/Fashion_recommendation_system/assets/111232798/a8fd3326-07f3-455a-b3d9-3d313178297a)

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact
For questions or feedback, please reach out to us at:

Email: niharikap958@gamil.com
GitHub: https://github.com/Niharika-002


Happy recommending! 😎


   
   
   
   
   
   
