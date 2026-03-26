# 💬 Code Comment Quality Analyzer (NLP)

An NLP-based tool that analyzes the **quality and type of comments in Python code**.
The system extracts comments from uploaded `.py` files and evaluates them using **Natural Language Processing techniques**.

---

# 🚀 Features

* Extract comments from Python source code
* Clean and preprocess comment text
* Classify comment types:

  * TODO
  * DEBUG
  * DOCSTRING
  * EXPLANATION
* Compute **comment quality scores**
* Interactive **Streamlit dashboard**
* Visual analytics and summaries

---

# 🧠 NLP Techniques Used

* Tokenization
* Text Cleaning
* TF-IDF concepts
* Rule-based classification
* Readability scoring

---

# 📊 Dashboard Capabilities

The dashboard allows users to:

* Upload a Python file
* Extract comments automatically
* View comment classification
* Analyze comment quality
* Explore visual insights through charts

---

# 📁 Project Structure

```
code-comment-quality-analyzer-nlp
│
├── notebooks
│   ├── comment_extraction.ipynb
│   └── comment_analysis.ipynb
│
├── dataset
│   └── comments_dataset_cleaned.csv
│
├── reports
│   └── comment_analysis_results.csv
│
├── app.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

Clone the repository:

```
git clone https://github.com/Venkateshpaitwar/code-comment-quality-analyzer-nlp.git
```

Navigate into the project directory:

```
cd code-comment-quality-analyzer-nlp
```

Install dependencies:

```
pip install -r requirements.txt
```

---

# ▶️ Running the Dashboard

Run the Streamlit application:

```
streamlit run app.py
```

The dashboard will open in your browser at:

```
http://localhost:8501
```

---

# 📷 Example Workflow

1. Upload a `.py` file
2. Extract comments automatically
3. Classify comment type
4. Calculate quality score
5. Visualize insights

---

# 📈 Example Output

| Comment                     | Type        | Quality Score |
| --------------------------- | ----------- | ------------- |
| TODO fix login bug          | TODO        | 0.52          |
| initialize user session     | EXPLANATION | 0.71          |
| return authentication token | DOCSTRING   | 0.89          |

---

# 🛠 Technologies Used

* Python
* Streamlit
* Pandas
* NLP techniques
* TextStat (readability scoring)

---

# 🎓 Academic Use

This project was developed as part of an **NLP mini project** demonstrating how natural language processing can be applied to **analyze and evaluate code comments in software repositories**.

---

# 👨‍💻 Author

Developed by **Venkatesh Paitwar**

---
