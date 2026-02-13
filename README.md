# Artificial Intelligence Algorithms and Mathematics - Labs

This repository contains lab assignments for the AIAM course. Each lab focuses on different aspects of data science, including machine learning, probability, and data preprocessing.

## 📂 Project Structure

```text
Lab/
├── Lab1/               # Basic NumPy Operations
│   └── Chao-Chung_Liu_Basic_NumPy_Operations_Lab1.html
│   └── Chao-Chung_Liu_Basic_NumPy_Operations_Lab1.ipynb
│   └── Lab 1.docx
├── Lab2/               # Coding_questions
│   ├── Lab2_dataset.csv
│   ├── AB_NYC_2019.csv
│   └── Chao-Chung_Liu_Coding_questions_Lab2.html
│   └── Chao-Chung_Liu_Coding_questions_Lab2.ipynb
│   └── Lab2.pdf
├── .gitignore          # Files to be ignored by Git
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

```

## 🚀 Lab Summaries
### Lab 1: Basic NumPy Operations
    * Goal: Practice using NumPy for 2-D arrays and solving systems of linear equations.

    * Key Tasks: Array slicing, reshaping, broadcasting, and matrix multiplication.

###  Lab 2: Coding_questions
    * Part A: Spam Classification

        * Compare GaussianNB and MultinomialNB models.

        * Used `CountVectorizer` for text processing.

    Result: MultinomialNB performed better for text classification.

    * Part B: Data Cleaning (AirBnB NYC)

        * Removed outliers using MAD (Median Absolute Deviation).

    Analyzed the relationship between `Room Type` and `Price`.

## 🛠️ Setup Instructions
1. Clone the repository:

```Bash
git clone [https://github.com/caatat741213/Artificial-Intelligence-Algorithms-and-Mathematics-s-Lab.git](https://github.com/caatat741213/Artificial-Intelligence-Algorithms-and-Mathematics-s-Lab.git)
cd Artificial-Intelligence-Algorithms-and-Mathematics-s-Lab

```

2. Create and activate a virtual environment:

```Bash
python -m venv venv
# On Windows:
.\venv\Scripts\activate

```

3. Install dependencies:

```Bash

pip install -r requirements.txt

```