# Sentiment Analysis on IMDB Movie Reviews

## Project Overview
This project performs **sentiment analysis** on the **IMDB dataset** containing 50,000 movie reviews. Each review is labeled as either **positive** or **negative**. The goal is to train a machine learning model that can accurately classify the sentiment of unseen reviews.

---

## Dataset

- **Source**: [Kaggle IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Size**: 50,000 labeled reviews
- **Type**: Supervised learning (binary classification)
- **Classes**: `positive`, `negative`

---

## Tech Stack

- Python
- Google Colab
- Scikit-learn
- Pandas
- Matplotlib

---

## Model Used

**Multinomial Naive Bayes Classifier**

### Why Naive Bayes?
- Works well with word frequency data
- Simple and fast for large datasets
- Performs well on high-dimensional text data
- Easy to interpret and implement
- Serves as a strong baseline model

---

## Preprocessing Steps

- Text cleaning (lowercasing, punctuation removal)
- Tokenization and vectorization using `CountVectorizer`
- Data splitting using `train_test_split`

---

## Model Evaluation

- Accuracy Score
- Confusion Matrix
- Visualization using `matplotlib`

---

## Results

- Achieved a solid accuracy on test data
- Fast training time with efficient performance
- Successfully predicted sentiment of unseen reviews

---

## How to Use

1. Upload `kaggle.json` to Colab to load the dataset
2. Run all notebook cells to train and evaluate the model
3. Modify the review inputs to test predictions

---

## Export

You can export the notebook as `.ipynb`, `.pdf`, or `.py` using **File > Download** in Google Colab.

---

## License

This project is for educational and academic purposes.
