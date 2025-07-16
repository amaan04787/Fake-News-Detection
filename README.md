# Fake-News-Detection
This project detects fake news articles using multiple machine learning classifiers, including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. The workflow covers data cleaning, text preprocessing, TF-IDF vectorization, model training, evaluation, and manual testing on custom inputs.


## Dataset

This project uses two datasets: `Fake.csv` and `True.csv`, which contain fake and real news articles respectively.

You can download them from Kaggle or other public sources and place them in the same directory as the Python script.

- [Download from Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

Make sure the files are named exactly:
- `Fake.csv`
- `True.csv`


## How to Run

1. **Install dependencies**

    Open your terminal or command prompt in the project directory and run:


2. **Prepare the data**

    Make sure the following files are in the same folder as `fake_news_detection.py`:
    - `Fake.csv`
    - `True.csv`

3. **Run the script**

    Execute the Python script:

4. **Test predictions**

   After running, you will be prompted to enter news text. Type or paste the text and press Enter to see predictions from all models.
