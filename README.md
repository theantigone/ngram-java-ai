# GenAI for Software Development (Ngram)

* [1 Introduction](#1-introduction)  
* [2 Getting Started](#2-getting-started)  
  * [2.1 Preparations](#21-preparations)  
  * [2.2 Install Packages](#22-install-packages)  
  * [2.3 Run N-gram](#23-run-n-gram)  
* [3 Report](#3-report)  

---

# **1. Introduction**  
This project explores **code completion in Java**, leveraging **N-gram language modeling**. The N-gram model predicts the next token in a sequence by learning the probability distributions of token occurrences in training data. The model selects the most probable token based on learned patterns, making it a fundamental technique in natural language processing and software engineering automation.  

---

# **2. Getting Started**  

This project is implemented in **Python 3.9+** and is compatible with **macOS, Linux, and Windows**.  

## **2.1 Preparations**  

(1) Clone the repository to your workspace:  
```shell
~ $ git clone https://github.com/theantigone/ngram-java-ai.git
```
(2) Navigate into the repository:
```shell
~ $ cd ngram-java-ai
~/ngram-java-ai $
```
(3) Set up a virtual environment and activate it:

For macOS/Linux:
```shell
~/ngram-java-ai $ python -m venv ./venv/
~/ngram-java-ai $ source venv/bin/activate
(venv) ~/ngram-java-ai $ 
```

To deactivate the virtual environment, use the command:
```shell
(venv) $ deactivate
```

## **2.2 Install Packages**

Install the required dependencies:
```shell
(venv) ~/ngram-java-ai $ pip install -r requirements.txt
```
## **2.3 Run N-gram**

(1) Run N-gram Demo

The script takes a corpus of Java methods as input and automatically identifies the best-performing model based on a specific N-value. It then evaluates the selected model on the test set extracted according to the assignment specifications.
Since the training corpus differs from both the instructor-provided dataset and our own dataset, we store the results in a file named results_provided_model.json to distinguish them accordingly.

Navigate to the ```src``` directory, then run:
```shell
(venv) ~/ngram-java-ai/src $ python ngram_model.py <student_corpus_text> <instructor_corpus_text>
```

## 3. Report

The assignment report is available inside the **reports** folder named **Assignment_Report.pdf**.


