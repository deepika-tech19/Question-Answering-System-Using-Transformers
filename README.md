📖 Overview

This project implements an intelligent **Question Answering (QA)** system capable of extracting the most relevant answer from a given context using **DistilBERT**, a lightweight Transformer model. The system is trained on the **SQuAD 2.0** dataset and demonstrates the practical application of Natural Language Processing (NLP) in AI.

---

## ✨ Key Features

- 🧠 Transformer-based Question Answering
- 📚 Uses the SQuAD 2.0 Dataset
- ⚡ Fast inference with DistilBERT
- 📊 Confidence score prediction
- 📈 Model performance evaluation
- 📉 Data visualization using Matplotlib
- 📝 Clean and well-structured implementation

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Hugging Face Transformers
- PyTorch
- Matplotlib
- Google Colab

---

## 📂 Dataset

**Dataset:** SQuAD 2.0

- 130,316 cleaned samples
- Context-based questions
- Human-annotated answers

---

## 🔄 Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Preprocessing
   │
   ▼
DistilBERT Model
   │
   ▼
Answer Prediction
   │
   ▼
Evaluation
   │
   ▼
Visualization
```

---

## 📊 Results

| Metric | Value |
|--------|-------|
| Model | DistilBERT |
| Dataset | SQuAD 2.0 |
| Accuracy | **88%** |
| Samples Evaluated | 100 |

---

## 📈 Visualizations

- 📊 Confidence Score Bar Chart
- 🥧 Accuracy Pie Chart
- 📉 Confidence Score Distribution

---

## 📁 Project Structure

```
Question-Answering-System-Using-Transformers
│
├── dataset/
├── notebook.ipynb
├── qa_model/
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/Question-Answering-System-Using-Transformers.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

```python
from transformers import pipeline

qa = pipeline(
    "question-answering",
    model="distilbert-base-cased-distilled-squad"
)
```

---

## 🎯 Future Scope

- 🌍 Multilingual Question Answering
- 🌐 Streamlit Web Application
- ☁️ Cloud Deployment
- 🤖 Fine-tuning on Custom Datasets
- 📱 REST API Integration

---

## 👩‍💻 Author

**Deepika**  
AI & Data Science Student

---

<div align="center">

### ⭐ If you like this project, consider giving it a Star!

Made with ❤️ using Python & Hugging Face Transformers

</div>
