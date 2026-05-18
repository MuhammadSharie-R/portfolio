
# Political Bias Detection in News

This is a machine learning project I built to analyze news articles and figure out their political bias (like left, center, or right). Here you will find the Python code, the steps I took to clean the text data, and the final models I trained.

## What it does

The goal here is to help people spot political echo chambers. The code takes raw news text, breaks it down into features the computer can understand, and then runs it through a few different classification models to predict the article's political leaning.

**Main steps in the code:**
*   **Text Cleaning:** Tokenizing the text, removing stop words, and getting the data ready for training.
*   **Feature Extraction:** TF-IDF, Lemmatization.
*   **Modeling:** Trying out different algorithms like Logistic Regression,SVM or Random Forest to see which one works best.

## The Data

I used the AllSides Media Bias dataset for this project. Because GitHub does not let you upload huge files, I could not include the raw CSV file directly in this repo.

*   You can download the dataset from: https://www.kaggle.com/datasets/ponssvvv/bias-clean
*   Just grab the file and drop it into the project folder before you run the notebook.

## Tools I Used

*   **Language:** Python
*   **Workspace:** Google Colab
*   **Libraries:** pandas, scikit-learn and NLTK
