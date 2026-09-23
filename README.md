# 🧠 Natural Language Processing Classification of Web Texts Combined with Deep Learning

<p align="center">
  <b>Deep Learning-Based Web Text Classification System</b>
</p>

<p align="center">
  An NLP project combining BERT contextual embeddings, BiGRU, CNN, and attention mechanisms for web text classification.
</p>

---

## 📌 About the Project

**Natural Language Processing Classification of Web Texts Combined with Deep Learning** is a project that focuses on classifying web text using Natural Language Processing (NLP) and deep learning techniques.

The proposed approach combines **BERT contextual embeddings** with parallel **Bidirectional Gated Recurrent Unit (BiGRU)** and **Convolutional Neural Network (CNN)** components. An attention mechanism is incorporated to help the model focus on relevant features. The learned representations are combined and passed through a linear layer and Softmax for classification.

The project also describes a web application developed using Django, with frontend technologies and MySQL database support.

---

## 🎯 Project Objectives

* Apply NLP techniques to web text classification.
* Use BERT to obtain contextual text representations.
* Combine BiGRU and CNN components to learn different text features.
* Incorporate attention into the classification architecture.
* Provide a web-based interface for interacting with the system.

---

## ✨ Key Features

* 📝 **Text Classification** – Classifies text using NLP and deep learning methods.
* 🧠 **BERT Embeddings** – Captures contextual information from text.
* 🔄 **BiGRU Network** – Learns sequential features from text.
* 🧩 **CNN Component** – Extracts local patterns and features.
* 🎯 **Attention Mechanism** – Helps the model focus on relevant representations.
* 🔗 **Feature Concatenation** – Combines learned features before classification.
* 🌐 **Django Web Application** – Provides the web application framework.
* 🗄️ **MySQL Database** – Supports database integration.

---

## 🛠️ Technologies Used

| Category             | Technology                       |
| -------------------- | -------------------------------- |
| Programming Language | Python 3.11.9                    |
| Web Framework        | Django                           |
| Database             | MySQL 8.0                        |
| Frontend             | HTML, CSS, JavaScript, Bootstrap |
| NLP                  | BERT                             |
| Deep Learning        | BiGRU, CNN, Attention            |
| Classification Layer | Linear Layer, Softmax            |

---

## 🏗️ System Architecture

The architecture uses BERT to generate contextual embeddings. These representations are processed through parallel BiGRU and CNN components. The features are then combined and passed through the classification layers.

```text
                 Input Web Text
                       │
                       ▼
              Text Preprocessing
                       │
                       ▼
                BERT Embeddings
                       │
                ┌──────┴──────┐
                ▼             ▼
              BiGRU           CNN
                │             │
                └──────┬──────┘
                       ▼
               Attention Mechanism
                       │
                       ▼
              Feature Concatenation
                       │
                       ▼
                  Linear Layer
                       │
                       ▼
                    Softmax
                       │
                       ▼
              Classification Output
```

---

## 🔬 Models and Approaches

The project report refers to the following model approaches:

* **BERT-BGCA**
* **OpenAI**
* **Ensemble**

Their exact implementation details and comparative results should be interpreted according to the project source code and evaluation documentation.

---

## 📊 Performance Metrics

The project report states the following evaluation values:

| Evaluation Metric | Reported Value |
| ----------------- | -------------: |
| Accuracy          |         95.21% |
| F1-Score          |         94.36% |

*These values are reported in the project documentation. Actual performance may depend on the dataset, preprocessing, training procedure, and evaluation methodology.*

---

## 🖥️ Project Screenshots

### 🏠 Home Page

![Home Page](screenshots/home.png)

### ✍️ Single Text Classification

![Single Text Classification](screenshots/single_text.png)

### 📂 File Upload

![File Upload](screenshots/file_upload.png)

### 📊 Classification Results

![Classification Results](screenshots/results.png)

### 📝 Batch Text Classification

![Batch Text Classification](screenshots/batch_text.png)

---

## 📁 Project Structure

```text
NLP-Web-Text-Classification/
│
├── docs/
│   ├── ARCHITECTURE.md
│   └── Project_Report.pdf
│
├── screenshots/
│   ├── batch_text.png
│   ├── file_upload.png
│   ├── home.png
│   ├── results.png
│   ├── single_text.png
│   └── README.md
│
├── src/
│   ├── forms/
│   │   └── README.md
│   ├── ml_models/
│   │   └── README.md
│   ├── utils/
│   │   └── README.md
│   └── README.md
│
├── .gitignore
├── DATASET.md
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation and Setup

### Prerequisites

* Python 3.11.9
* MySQL 8.0
* Git

### 1. Clone the Repository

```bash
git clone https://github.com/ChAnjali304/NLP-Web-Text-Classification.git
```

### 2. Open the Project Directory

```bash
cd NLP-Web-Text-Classification
```

If the project files are inside the nested `NLP-Web-Text-Classification` folder, open that folder as well.

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure the Database

Configure the MySQL database connection according to the project's Django settings.

### 6. Run the Application

The Django run commands and database migration steps must be confirmed against the actual application source code before running the project.

---

## 📚 Documentation

* **Architecture:** `docs/ARCHITECTURE.md`
* **Project Report:** `docs/Project_Report.pdf`
* **Dataset Information:** `DATASET.md`

---

## ⚠️ Note

This repository's documentation and screenshots describe the project. To install and run the complete application, the required application source code, model files, configuration, and dependencies must also be available.

---

## 👩‍💻 Author

**Anjali**

GitHub: [ChAnjali304](https://github.com/ChAnjali304)

---

<p align="center">
  ⭐ Thank you for visiting this project!
</p>
