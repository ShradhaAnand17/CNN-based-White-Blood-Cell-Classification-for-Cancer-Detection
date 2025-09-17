# White Blood Cell Classification using CNN

This repository implements a **Convolutional Neural Network (CNN)** for classifying **normal and malignant white blood cells (WBCs)**.  
The framework demonstrates potential for **leukemia detection** and **automated diagnostic support** by analyzing WBC morphology from image datasets.

## Published paper and Citation
- Link: https://ieeexplore.ieee.org/document/10817028
- Citation: Shivandappa, T. N. Gundawar, S. A. Bandikatte, S. A. Mulimani, R. D. Umesh and D. Kori, "Image-Based WBC Analysis: A Machine Learning Approach for Cancer Detection," 2024 8th International Conference on Computational System and Information Technology for Sustainable Solutions (CSITSS), Bengaluru, India, 2024, pp. 1-6, doi: 10.1109/CSITSS64042.2024.10817028. 

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



