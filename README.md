**Eye Disease Detection Using Machine Learning**

**Overview**

This project focuses on detecting and analyzing more than eight different eye diseases using machine learning models. The approach includes data preprocessing, training a model to predict disease presence, and developing a web application for real-time predictions. The model achieves a high accuracy of **97%**, making it a reliable tool for diagnosing eye diseases.

**Project Structure**

*   **eye-disease.ipynb** - Jupyter Notebook that handles data preprocessing, model training, and evaluation.
    
*   **app.py** - Flask-based web application for inputting medical data and receiving eye disease predictions.
    
*   **requirements.txt** - List of dependencies required to run the project.
    

**Eye Diseases Analyzed**

The model is trained to detect and analyze the following eye diseases:

1.  Cataract
    
2.  Glaucoma
    
3.  Diabetic Retinopathy
    
4.  Macular Degeneration
    
5.  Keratitis
    
6.  Uveitis
    
7.  Conjunctivitis
    
8.  Retinitis Pigmentosa
    
9.  Myopia (Nearsightedness)
    

**Setup and Installation**

1.  clone https://github.com/Krishna17-bit/Eye-disease-detection.git
2.  cd eye-disease-detection
    
3.  pip install -r requirements.txt
    

**Data Processing and Model Training**

1.  **Data Preprocessing**:
    
    *   Load and preprocess data with various image processing techniques.
        
    *   Normalize images, resize them for consistency, and apply data augmentation.
        
2.  **Model Training**:
    
    *   Train a deep learning model on preprocessed images, using convolutional neural networks (CNN) for feature extraction.
        
    *   Evaluate the model’s performance across multiple diseases, achieving an overall accuracy of **97%**.
        
3.  **Model Evaluation**:
    
    *   Evaluate the model using metrics like accuracy, precision, and recall for each eye disease.
        
    *   Perform cross-validation to ensure robust performance across the dataset.
        

**Web Application**

*   **Real-Time Prediction**: Use the web app to input patient data and receive a prediction on possible eye diseases.
    
*   **Deployment**: The app is built with Flask, allowing for easy deployment and user interaction.
    

**Usage**

1.   python app.pyAccess the app in a browser at http://127.0.0.1:5000.
    
2.  **Make Predictions**:Use the web interface to upload eye images and get real-time predictions on potential eye diseases.
    

**Results**

*   The model achieves **97% accuracy**, providing reliable predictions across more than eight eye diseases.
    
*   Precision and recall metrics are optimized to ensure minimal false positives and negatives.
    

**Key Takeaways**

*   **High Accuracy**: 97% accuracy ensures effective diagnosis for multiple eye diseases.
    
*   **Versatility**: Model can detect more than eight distinct eye diseases, providing a comprehensive diagnostic tool.
