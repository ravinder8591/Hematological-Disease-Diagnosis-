# An Efficient CNN-Based Framework for Automated Blood Cell Classification in Hematological Disease Diagnosis

## 👨‍🎓 Authors

- **Ravinder Singh** (ID: 2210992144)  
- **Rishav Nath Kaura** (ID: 2210992160)  
- **Rajat Chauhan** (ID: 2210992131)  

Department of Computer Science and Engineering  
Chitkara University Institute of Engineering and Technology  
Chitkara University, Rajpura, Punjab, India  

---

## 📌 Project Overview

This project presents a **Convolutional Neural Network (CNN)-based framework** for automated blood cell classification to assist in hematological disease diagnosis. The system classifies microscopic blood cell images into four categories:

- Benign  
- Malignant Pre-B  
- Malignant Pro-B  
- Malignant Early Pre-B  

The proposed model helps in improving the speed, accuracy, and reliability of blood cell classification while reducing dependency on manual microscopic analysis.

The framework achieved an overall classification accuracy of **98.76%**.

---

## 🩸 Dataset Information

The dataset used in this project is:

- **ALL Challenge Dataset of ISBI 2019 (C-NMC 2019)**  
- Source: Kaggle / The Cancer Imaging Archive (TCIA)

### Dataset Details
- Total Images: **3,242**
- Classes:
  - Benign
  - Malignant Pre-B
  - Malignant Pro-B
  - Malignant Early Pre-B

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries & Frameworks
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras
Windows
</> Bash 
venv\Scripts\activate

Linux / macOS
</> Bash

source venv/bin/activate

Install Dependencies
</> Bash

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow keras
💻 Running the Project

Open the notebook file in:

Jupyter Notebook
JupyterLab
Google Colab
</> Bash
jupyter notebook

Then open:
</> Bash

blood_cell_classification.ipynb
🧠 CNN Model Workflow

The project follows the following workflow:

Dataset Collection
Image Preprocessing
Resizing
Normalization
Image Enhancement
CNN Model Development
Model Training
Blood Cell Classification
Performance Evaluation
📊 Model Performance
Performance Metrics
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
Final Accuracy
98.76%

📉 Visualizations

The project generates several visualizations for analysis and evaluation:

Generated Graphs
Training Accuracy Curve
Validation Accuracy Curve
Training Loss Curve
Validation Loss Curve
Confusion Matrix
Blood Cell Class Distribution
Analysis Performed
CNN learning behavior
Classification performance
Misclassification analysis
Dataset distribution analysis

🔬 Features of the Proposed System


Automated blood cell classification
Deep learning-based feature extraction
Multi-class blood cell prediction
High classification accuracy
Reduced manual diagnostic effort
Supports hematological disease diagnosis


🚀 Future Scope


Use larger real-world clinical datasets
Implement advanced architectures such as:
ResNet
EfficientNet
Vision Transformers
Integrate Explainable AI (XAI)
Develop a real-time clinical web application
Integrate with hospital diagnostic systems


📄 Research Paper Title

An Efficient CNN-Based Framework for Automated Blood Cell Classification in Hematological Disease Diagnosis

📚 References

Cheuque, C., et al. “An Efficient Multi-Level Convolutional Neural Network Approach for White Blood Cells Classification,” Diagnostics, 2022.
Shahzad, M., et al. “Blood Cell Image Segmentation and Classification: A Systematic Review,” PeerJ Computer Science, 2024.
Jain, E., et al. “Swin Transformer and Momentum Contrast (MoCo) in Leukemia Diagnostics,” IEEE Access, 2025.
Mourya, S., et al. “ALL Challenge Dataset of ISBI 2019 (C-NMC 2019),” The Cancer Imaging Archive, 2019.
📜 License

This project is developed for academic and research purposes under Chitkara University.

Distributed under the MIT License.
