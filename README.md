# GDDES - Gynecological Disease Diagnosis Expert System

---

## 🧬 Project Overview
GDDES is an intelligent medical expert system that predicts and diagnoses gynecological conditions using machine learning and natural language processing (NLP).  
The system processes structured and unstructured patient data to assist healthcare professionals and patients with faster, more accurate diagnosis.

---

## 🚀 Features
- Machine Learning-based Disease Prediction  
- NLP-powered Symptom Analysis  
- User-Friendly Interface for easy interaction  
- High-accuracy diagnosis using trained models  
- Future-ready system with scalability for new diseases

---

## 📚 Technologies Used
- **Python 3.10+**
- **Scikit-learn** - Machine Learning algorithms
- **Pandas** - Data processing
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Visualization
- **NLTK / spaCy** - NLP processing (choose one based on your implementation)
- **Tkinter / Streamlit** - (for GUI or web interface)
- **Joblib** - Model serialization

---

## 🛠️ Installation

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/GDDES.git
cd GDDES
```

2. **Create a Virtual Environment (recommended)**
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```

3. **Install Requirements**
```bash
pip install -r requirements.txt
```

---

## ⚙️ Requirements.txt Content

```
pandas
numpy
scikit-learn
matplotlib
seaborn
nltk
spacy
streamlit
joblib
tk
```

(If you’re using **Streamlit** for frontend, add it. If using **Tkinter** only, skip `streamlit`.)

---

## 🏗️ Project Structure

```plaintext
GDDES/
│
├── data/                  # Preprocessed datasets
├── models/                # Trained ML models (.joblib files)
├── utils/                 # Helper functions (NLP preprocessing, ML utilities)
├── frontend/              # GUI or WebApp code (Streamlit or Tkinter)
├── main.py                # Entry point to run the application
├── requirements.txt       # List of all dependencies
└── README.md              # Project documentation
```

---

## 🔥 How to Run the Project

### For Streamlit Web App:
```bash
streamlit run frontend/app.py
```

### For Tkinter GUI App:
```bash
python frontend/app.py
```

---

## 📈 Model Details
- **Algorithm Used**: Random Forest, Logistic Regression, Decision Trees (ensemble methods if applicable)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score
- **Performance**: High accuracy (~90%+) on validation dataset

---

## 📌 Future Enhancements
- Adding more gynecological diseases
- Deep Learning models (LSTM for patient history)
- Deploy as a mobile app
- Integrate with hospital management systems

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 🧑‍💻 Author
**PK** (Praveen Kumar)

---

## 🛡️ License
This project is licensed under the MIT License.

---

# 📋 Extensions / Libraries You Need

| Library | Usage |
|:--------|:------|
| **numpy** | Numerical processing |
| **pandas** | Data analysis |
| **scikit-learn** | Machine learning |
| **matplotlib** | Plotting graphs |
| **seaborn** | Statistical visualization |
| **nltk / spacy** | Natural Language Processing |
| **joblib** | Saving/loading ML models |
| **streamlit** (optional) | Web interface |
| **tkinter** (optional) | GUI interface |
| **python-dotenv** (optional) | If you use environment files |

🔢 Also make sure:
- Python 3.10+ is installed  
- NLTK or spaCy models are downloaded (like `punkt`, `en_core_web_sm` if using spaCy)

