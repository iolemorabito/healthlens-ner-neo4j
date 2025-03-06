# 🏥 HealthLens - Clinical Knowledge Extraction & Visualization

## 📖 Overview
HealthLens is a system designed to **extract and analyze unstructured textual data** from **clinical notes written in Italian**, with the goal of building a **Knowledge Graph** for analytics, reporting, and data visualization. The system provides a structured and interactive way to process clinical data, facilitating **better insights and decision-making** for healthcare professionals.

## 🎯 Key Objectives

### 🔹 **Automated Clinical Information Extraction**
- Uses **Named Entity Recognition (NER)** and **Relation Extraction (RE)** to identify and classify key medical concepts such as:
  - Diseases
  - Symptoms
  - Medications
  - Lab tests & procedures

### 🔹 **Knowledge Graph Construction**
- Structures extracted medical information into a **Knowledge Graph**, representing relationships between different medical concepts.
- Enables **better accessibility, visualization, and understanding** of patient conditions and clinical histories.

### 🔹 **Interactive Dashboard for Data Visualization**
- **Developed using Streamlit**, providing an intuitive and customizable user interface.
- Enables **doctors and nurses** to:
  - View extracted clinical data in a **clear and structured format**.
  - Interact with the **Knowledge Graph**.
  - Customize reports and analytics based on specific needs.

## 🛠️ Tech Stack
- **Natural Language Processing (NLP):** Spacy, Transformers
- **Data Processing:** Pandas, Numpy
- **Graph Database:** Neo4j, NetworkX
- **Frontend:** Streamlit for visualization

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/iolemorabito/healthlens-ner-neo4j.git
cd HealthLens
```

### 2️⃣ Set Up a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate    # On Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
streamlit run app.py
```


https://github.com/user-attachments/assets/d8ac75f4-4a99-4faa-bace-25deef293760



## 📊 Future Enhancements
- Expand **NER models** to support multiple languages
- Integrate **real-time clinical data processing**
- Improve **graph-based queries** for better analytics


