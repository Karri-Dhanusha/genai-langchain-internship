# 🤖 AI Resume Screening System with LangChain

## 📌 Project Overview

This project is an **AI-powered Resume Screening System** that evaluates candidate resumes against a given job description using **LLMs (Large Language Models)**.

It automates the hiring process by performing:

* Skill extraction
* Resume-job matching
* Candidate scoring (0–100)
* Explainable feedback

---

## 🎯 Objective

To build a **modular and explainable AI system** that can:

* Analyze resumes intelligently
* Compare them with job requirements
* Provide transparent and accurate evaluation results

---

## 🚀 Key Features

✅ Automated skill extraction
✅ Resume vs Job matching analysis
✅ Intelligent candidate scoring
✅ Clear explanation of results
✅ Modular pipeline using LangChain
✅ Debugging support with LangSmith (optional)

---

## 🛠️ Tech Stack

* **Python**
* **LangChain**
* **Hugging Face Transformers**
* **Google FLAN-T5 Model**
* **Google Colab**

---

## 📂 Project Structure

```
AI-Resume-Screening-System/
│── Task_3_AI_Resume_Screening_System.ipynb
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install Dependencies

```bash
pip install langchain langchain-community langchain-openai transformers
```

### 2️⃣ (Important) Fix Transformers Version

```bash
pip install transformers==4.41.2
```

---

## ▶️ How It Works

### Step 1: Skill Extraction

Extracts:

* Skills
* Tools
* Experience

---

### Step 2: Matching Logic

Compares resume with job description:

* Matching Skills
* Missing Skills

---

### Step 3: Scoring

Assigns a score between **0–100** based on:

* Skill relevance
* Experience match

---

### Step 4: Explanation

Provides:

* Strengths
* Weaknesses
* Final justification

---

## 🔄 Pipeline Flow

```
Resume → Extraction → Matching → Scoring → Explanation
```

---

## 📊 Sample Results

### 🟢 Strong Candidate

* High skill match
* Meets experience requirement
* Score: 85–95

### 🟡 Average Candidate

* Partial skill match
* Less experience
* Score: 50–70

### 🔴 Weak Candidate

* No relevant skills
* No experience
* Score: 0–30

---

## 🐞 Debugging & Tracing

LangSmith can be used for:

* Monitoring LLM responses
* Debugging pipeline
* Visualizing execution

*(Optional setup required)*

---

## ⚠️ Known Issues & Fixes

### Issue: `Unknown task text2text-generation`

✔ Fix:

```bash
pip install transformers==4.41.2
```

---

### Issue: LangSmith 403 Error

✔ Fix:

```python
os.environ["LANGCHAIN_TRACING_V2"] = "false"
```

---

## 📌 Future Improvements

* Add Streamlit UI
* Use advanced LLMs (GPT-4 / APIs)
* Upload real resumes (PDF parsing)
* Improve scoring logic

---

## 🙌 Conclusion

This project demonstrates:

* Real-world AI hiring automation
* LLM-based decision systems
* Explainable AI pipeline

It reflects how modern companies use AI for **smart recruitment systems**.

---

## 👩‍💻 Author

**Karri Dhanusha**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
