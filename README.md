# BRAINDEAD 2025: The Ultimate Data Analysis & Machine Learning Challenge


![image](https://github.com/user-attachments/assets/d355784f-c092-417b-830f-6894ed05dc50)



## IPL Data Analysis & Winner Prediction | Research Article Summarization


This repository contains two machine learning and data science projects:

1.IPL Data Analysis & Winner Prediction – A statistical and ML-based approach to analyze past IPL performance and predict the winner of IPL 2025.

2.Research Article Summarization – An NLP-driven project that automates summarization of research articles using extractive and abstractive techniques.

## Project 1: IPL Data Analysis & Winner Prediction

Objective : The goal is to analyze historical IPL data, extract key performance indicators, and apply machine learning techniques to predict the likely winner of IPL 2025.


## Features


✔ Data cleaning and preprocessing of IPL datasets

✔ Player and team performance analysis using statistics

✔ Implementation of ML models for winner prediction

✔ Visualization of key trends in IPL history



**Folder Structure:**
```bash
/IPL-Winner-Prediction/
│── data/                 # Raw & cleaned IPL datasets
│── notebooks/            # Jupyter Notebooks for data analysis & ML modeling
│── scripts/              # Python scripts for data preprocessing, training
│── models/               # Trained ML models
│── results/              # Outputs, visualizations, and performance metrics
│── README.md             # Project documentation
│── requirements.txt      # Dependencies list
│── .gitignore            # Files to be ignored in Git
```


**Dataset:**

Source:
Kaggle,  IPL official records,[CricSheet](https://cricsheet.org/) (IPL Dataset)


**Contents:**

•Team and player stats from past IPL seasons

•Batting, bowling, and match performance metrics

•Match results, venues, and other influencing factors

## Installation & Usage:

1.Clone the repository

```bash
git clone https://github.com/rootism/braindead25.git
cd braindead25
```

2.Install dependencies

```bash
pip install -r requirements.txt
```

3.Run the Jupyter Notebook


4.Execute the analysis pipeline
Open ` notebooks/braindead(IPL)(1).ipynb ` and run all cells.



## Machine Learning Models Used

• Random Forest Classifier – Predict match outcomes

• XGBoost – Boosted decision trees for accuracy

• Neural Networks – Deep learning-based forecasting

• Logistic Regression – Baseline model



## Results & Insights:


• Player Rankings: Identifies top-performing batsmen & bowlers

• Match Outcome Predictions: Determines match-winning probabilities

• 2025 Winner Prediction: Forecasts the most probable IPL champion


## Project 2: Research Article Summarization

Objective : This project automates research paper summarization using NLP techniques to generate concise, informative summaries.


## Features


✔  Supports both extractive and abstractive summarization

✔ Uses pre-trained transformer models like BART & T5

✔ Evaluates summaries using ROUGE and BLEU scores

✔ Customizable summary length



**Folder Structure:**
```bash
/Research-Article-Summarization/
│── data/                 # Dataset of research papers
│── notebooks/            # Jupyter notebooks for NLP experiments
│── scripts/              # Python scripts for text preprocessing & model training
│── models/               # Pre-trained summarization models
│── results/              # Summaries & evaluation metrics
│── README.md             # Project documentation
│── requirements.txt      # Dependencies list
│── .gitignore            # Files to be ignored in Git

```


**Dataset:**

Source: 

•Open-access repositories such as arXiv; Clement, C.B., Bierbaum, M., O'Keeffe, K.P. and Alemi, A.A., 2019. On the use of arxiv as a dataset. arXiv preprint arXiv:1905.00075.

•Kaggle datasets containing research papers and abstracts

•U.S. National Library of Medicine (PubMed Dataset)

**Contents:**

• Full research papers (Abstract, Introduction, Methods, Results, Conclusion)

•Extracted abstracts for comparison with generated summaries

• Metadata (Title, Authors, Publication Year, DOI)



## Installation & Usage:

1.Clone the repository

```bash
git clone https://github.com/rootism/braindead25.git
cd braindead25
```

2.Install dependencies

```bash
pip install -r requirements.txt
```

3.Run the Jupyter Notebook


4.Execute the summarization pipeline
Open ` notebooks/Research_Article_Summarization.ipynb ` and run all cells.



## NLP Techniques Used

• Text Preprocessing: Tokenization, Stopword Removal, Lemmatization

•  Extractive Summarization: TextRank, TF-IDF

• Abstractive Summarization: BART, T5

• Evaluation Metrics: ROUGE Score, BLEU Score



## Results & Insights:


• High-Quality Summaries: 80%+ accuracy in retaining key research insights

• Comparison of NLP Models: Identifies the best summarization method

• Real-World Applications: Helps researchers quickly analyze papers

## License
This project is licensed under the MIT License








