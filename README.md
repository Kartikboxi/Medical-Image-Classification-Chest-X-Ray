# Medical Image Classification – Chest X-Ray

## 📌 Overview  
This project focuses on **Chest X-ray image classification** to detect **COVID-19** and other lung conditions.  
We implemented and compared three different approaches:  
- A **custom CNN model** built from scratch  
- A **VGG16** model (transfer learning)  
- A **ResNet50** model (transfer learning)  

The workflow includes dataset preprocessing, model training, evaluation, and visualization of results.

---

## ✨ Features  
- Preprocessing of chest X-ray images (resizing, normalization, augmentation)  
- CNN architecture for medical image classification  
- Training and validation with performance tracking  
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score  
- Confusion matrix and visualization of predictions  

---

## 📂 Repository Structure  
```bash
├── Covid_19_CNN.ipynb # Core notebook implementing the pipeline
└── README.md # Project documentation
```


---

## ⚙️ Installation  


# Clone the repository
```bash
git clone https://github.com/Kartikboxi/Medical-Image-Classification-Chest-X-Ray.git
cd Medical-Image-Classification-Chest-X-Ray
```

# (Optional) Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

# Install dependencies
```bash
pip install -r requirements.txt
If no requirements.txt exists, create one with the following (adjust as needed):

nginx
Copy code
numpy
pandas
matplotlib
seaborn
scikit-learn
tensorflow     # or torch, depending on your implementation
opencv-python
```

## 📊 Expected Results
Training & validation loss/accuracy plots

Confusion matrix and classification report

ROC curve (if implemented)

