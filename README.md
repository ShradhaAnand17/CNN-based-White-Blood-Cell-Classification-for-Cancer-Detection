# White Blood Cell Classification using CNN

This repository implements a **Convolutional Neural Network (CNN)** for classifying **normal and malignant white blood cells (WBCs)**.  
The framework demonstrates potential for **leukemia detection** and **automated diagnostic support** by analyzing WBC morphology from image datasets.

## 🧑‍💻 Methodology
1. **Data Preprocessing**  
   - Images resized to 256x256  
   - One-hot encoded labels  
   - Train/validation/test split  

2. **Model Architecture**  
   - Rescaling layer  
   - Convolution + MaxPooling layers  
   - Dense fully connected layers  
   - Output: softmax (4 classes)  

3. **Training & Evaluation**  
   - Optimizer: Adam  
   - Loss: Categorical Crossentropy  
   - Epochs: 5  
   - Metrics: Accuracy, Confusion Matrix, Classification Report  

## 📊 Results
- CNN successfully classified normal vs malignant WBCs  
- Classification metrics (precision, recall, F1-score) obtained  
- Visualization included:  
  - Training vs validation loss/accuracy curves  
  - Confusion matrix  
  - Random predictions vs true labels

## 🛠 Requirements
- Python 3.8+
- TensorFlow 2.x
- NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## 📌 Applications
- Automated screening for leukemia and other blood cancers
- Clinical decision support for pathologists
- Basis for research in hematology and medical image analysis



