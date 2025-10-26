### Project for CSE 4878: Machine Learning and Data Mining Lab (Spring 2022)

- **Analyzed datasets from two different sources:**
  - [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic) [Modality: Structured (tabular)] — Contains features extracted from digitized images of fine needle aspirates (FNA) of breast masses. These features describe the characteristics of the cell nuclei present in the images.  
  - [Breast Histopathology Images Dataset](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images/data) [Modality: Image] — Comprises image patches of Invasive Ductal Carcinoma (IDC), the most common subtype of breast cancer.  

- **Malignant vs. Benign Classification:**  
  Preprocessed the Breast Cancer Wisconsin (Diagnostic) dataset by handling missing values, removing highly correlated features, and applying feature scaling. Trained models using Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, and Gradient Boosting classifiers, then ranked their performance based on classification scores.  

- **Ductal Carcinoma (IDC) Detection:**  
  Downsampled the dataset to handle class imbalance and developed a Convolutional Neural Network (CNN), which was fine-tuned for the IDC classification task.  

- **Frameworks/Tools Used:**  
  TensorFlow, scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, OpenCV
