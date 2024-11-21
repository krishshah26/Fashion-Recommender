
# Fashion Recommendation System

**Overview**

The Fashion Recommendation System is a web application that allows users to upload images of fashion items (e.g., clothes, shoes, accessories) and receive recommendations for visually similar items.

The system uses:
- The system uses a pre-trained ResNet50 model for feature extraction and K-Nearest Neighbors (KNN) for similarity matching.
- A curated dataset of ~5,400 fashion item images forms the basis for recommendations.
- Each image in the dataset is preprocessed to extract a 2048-dimensional feature vector, stored in embeddings.pkl.

**Project Features**

**main.py:** Implements the web application using Streamlit. It handles file uploads, feature extraction, similarity search, and displays the recommendations.

**app.py:** Preprocesses the dataset in the images/ folder, extracts features using ResNet50, and saves the embeddings and filenames to embeddings.pkl and filenames.pkl.

**test.py:** A standalone script to test the feature extraction and recommendation functionality using a sample image.




## Tech Stack

The following tools and technologies are used in this project:

### **Frontend**
- **Streamlit**: Interactive web interface for uploading images and displaying recommendations.

### **Backend**
- **TensorFlow/Keras**: 
  - **ResNet50**: Pre-trained model (ImageNet) for extracting 2048-dimensional feature vectors.
- **scikit-learn**: 
  - **K-Nearest Neighbors (KNN)**: Algorithm to find similar items based on feature vectors.
- **Python Standard Library**:
  - `os`: For file management.
  - `pickle`: For saving and loading precomputed embeddings and filenames.
  - `Pillow`: For image handling and preprocessing.

### **Testing and Utilities**
- **OpenCV**: For testing and visualizing recommendations in `test.py`.
- **tqdm**: For displaying progress during dataset preprocessing.





## Dataset


*Download the dataset:*
https://kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset


## 🚀 About Me
Hello! 👋 My name is Krish Shah, and I am a passionate Data Analyst and aspiring Data Engineer with a strong foundation in data-driven problem-solving and technical innovation. With a keen interest in leveraging technology to extract meaningful insights from complex datasets, I specialize in creating robust, scalable solutions for data analysis and visualization.

