
# Fake News Detection with Naive Bayes and Logistic Regression

This project aims to tackle the growing issue of misinformation by developing machine learning models that can classify news articles as **fake** or **real**. Two popular models, **Naive Bayes** and **Logistic Regression**, are used for this task, and their performance is compared using accuracy metrics.

## Features

- **Model comparison**: Evaluate the effectiveness of Naive Bayes vs Logistic Regression in detecting fake news.
- **Data visualization**: Visualize the dataset's distribution of fake and real news articles.
- **Preprocessing**: Tokenization, vectorization, and cleaning of text data before feeding it into the models.
- **Performance metrics**: Accuracy, precision, recall, and F1-score are calculated for both models.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/mnbl/Fake-News-Detection
   cd Fake-News-Detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Project

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   
2. Run the notebook file `Fake News Classifier.ipynb` to train and evaluate the models.

The notebook walks through the following steps:
- Data loading and preprocessing
- Training the models (Naive Bayes and Logistic Regression)
- Evaluation of models using various metrics
- Visualization of results

## Dataset

The project uses two CSV files that can be found in the repository:
- `kaggle_fake_train.csv`: This training dataset contains labelled examples of fake and real news articles.
- `kaggle_fake_test.csv`: This is the test dataset used to evaluate the performance of the models.

## Results

After training both models, the project provides a comparison based on accuracy and other performance metrics. The results will help us understand which model performs better in detecting fake news, which is critical in the current information age.

## Contributions

Feel free to fork this project and submit pull requests if you would like to contribute improvements or additional features!
