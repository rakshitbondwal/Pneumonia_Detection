This project uses deep learning to detect pneumonia from chest X-ray images. A Convolutional Neural Network (CNN) is trained on the Chest X-Ray Pneumonia dataset to classify images as Normal or Pneumonia.

📂 Dataset :

Dataset: Chest X-Ray Pneumonia Train Set: For model training Validation Set: For hyperparameter tuning Test Set: For performance evaluation

🚀 Model Overview :

The CNN model consists of: ✅ Convolutional Layers for feature extraction ✅ MaxPooling Layers for dimensionality reduction ✅ Dense Layers for classification ✅ Dropout Layers to prevent overfitting

🔹 Training Details

Loss Function: Binary Cross-Entropy Batch Size: 32 Epochs: 25

📊 Results

📌 Accuracy: ~85-95% 📌 Precision & Recall: ~80-95%

🛠️ How to Run

1️⃣ Clone the repository : git clone https://github.com/your-username/Pneumonia-Detection.git cd Pneumonia-Detection

2️⃣ Install dependencies : pip install -r requirements.txt

3️⃣ Run the notebook : jupyter notebook Pneumonia_Detection.ipynb

🎯 Future Scope 📌 Implement Transfer Learning (e.g., ResNet, VGG16) 📌 Deploy as a web app using Flask/FastAPI 📌 Improve model performance with hyperparameter tuning
