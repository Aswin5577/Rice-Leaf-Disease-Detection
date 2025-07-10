# 🌾 Rice Leaf Disease Detection Using CNN

This project uses deep learning to classify rice leaf diseases—**Leaf Smut**, **Brown Spot**, and **Bacterial Leaf Blight**—from image data. It’s designed to support early disease identification in agriculture using a lightweight CNN model.

## 📁 Dataset

- **Total images**: 120 JPG files  
- **Classes**: Leaf Smut, Brown Spot, Bacterial Leaf Blight  
- Each class contains 40 labeled images  
- Images are stored in class-wise folders for easy loading

## 🧠 Approach

- Preprocessed images (resizing, normalization)
- Applied **data augmentation** to expand training set virtually
- Used **transfer learning** with MobileNetV2 to build a classification model
- Evaluated performance using accuracy, precision, recall, and F1-score

## 🔧 Tools & Technologies

- Python  
- TensorFlow / Keras  
- OpenCV  
- Matplotlib & Seaborn  
- NumPy & Pandas

## 📊 Results

- Achieved ~90–95% accuracy on validation data  
- Model successfully distinguishes between visually similar leaf diseases  
- Confusion matrix and metrics indicate good generalization

## 🚀 How to Run

1. Clone this repo  
2. Place dataset in `/data/` folder (class-wise subfolders)
3. Run `rice_disease_classifier.ipynb` notebook

## 📚 Future Scope

- Deploy as a mobile or web-based app for farmers  
- Expand dataset with more varied and real-field images  
- Explore real-time detection using camera feeds

## 🧑‍🔬 Author

- Aswin  
- Passionate about applying ML to agriculture and societal benefit

---
