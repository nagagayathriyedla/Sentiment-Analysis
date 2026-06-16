# Sentiment Analysis Using TextBlob

## Project Overview
This project performs sentiment analysis on Twitter data using Python and the TextBlob library. The model analyzes the text of tweets and classifies them into positive, negative, or neutral sentiments. The predicted results are compared with the existing sentiment labels in the dataset to evaluate performance.

## Features
- Loads and processes Twitter sentiment data using Pandas
- Performs sentiment prediction using TextBlob
- Classifies tweets as positive, negative, or neutral
- Compares predicted sentiments with actual sentiment labels
- Calculates model accuracy
- Saves the predicted results into a CSV file
- Visualizes sentiment distribution using a bar chart

## Technologies Used
- Python
- Pandas
- TextBlob
- Matplotlib
- Google Colab

## Dataset Information
The dataset contains:
- Tweet text
- Actual sentiment labels (positive, negative, neutral)
- User information such as age group, country, and tweet time

## Project Workflow
1. Import required Python libraries.
2. Load the Twitter dataset using Pandas.
3. Apply TextBlob sentiment analysis to each tweet.
4. Generate predicted sentiment labels.
5. Compare predictions with actual labels.
6. Calculate the prediction accuracy.
7. Save the final results into `sentiment_results.csv`.
8. Display a bar chart showing sentiment distribution.

## Results
- TextBlob prediction accuracy achieved: **59.20%**
- Generated a CSV file containing original data and predicted sentiments.
- Visualized sentiment distribution using a bar chart.

## Project Files
```
Sentiment-Analysis-Project
│
├── sentiment_analysis.ipynb    # Main notebook containing the complete code
├── Reviews.csv                 # Original Twitter sentiment dataset
├── sentiment_results.csv       # Dataset with predicted sentiments
├── README.md                   # Project documentation
└── requirements.txt            # Required Python libraries
```

## How to Run
1. Open the notebook in Google Colab.
2. Upload the `Reviews.csv` dataset.
3. Run all the cells in the notebook.
4. View the sentiment predictions, accuracy score, and visualization.

## Future Improvements
- Improve accuracy using machine learning or deep learning models.
- Perform text preprocessing such as removing URLs, punctuation, and stop words.
- Try advanced NLP models for better sentiment classification.

## Author
**Your Name**
