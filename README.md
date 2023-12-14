## US Airline Sentiment Analysis

This repository contains the analysis of sentiment in tweets about US airlines. The data was collected in February 2015 and comprises tweets classified as positive, negative, and neutral, along with further categorization of negative reasons.

### Data

* **Source:** Twitter
* **Collection Period:** February 2015
* **Content:** Tweets about US airlines
* **Labels:**
    * Sentiment: positive, negative, neutral
    * Negative reasons (optional): late flight, rude service, bad experience, etc.

### Analysis

This repository presents analysis performed on the aforementioned data, focusing on:

* **Overall Sentiment Distribution:** Exploring the percentage of positive, negative, and neutral tweets.
* **Reason-based Analysis:** Investigating the most frequent reasons for negative tweets.
* **Airline Comparison:** Comparing sentiment trends across different US airlines.
* **Temporal Analysis:** Examining how sentiment changes over time.

### Tools & Technologies

* Programming language: Python
* Libraries: pandas, matplotlib, nltk, scikit-learn 

### Included Files

* `notebooks/airline_sentiment_exploration.ipynb`: Jupyter notebook with interactive analysis and visualizations.
* `README.md`: This file (you're reading it now!)

### Getting Started

1. Clone this repository.
2. Install the required Python libraries: `pip install pandas matplotlib nltk scikit-learn`
3. Run the analysis script: `python analysis/sentiment_analysis.py`
4. Open the Jupyter notebook: `jupyter notebook notebooks/airline_sentiment_exploration.ipynb`

### Contributing

This is an open-source project, and I welcome contributions! Feel free to fork this repository, suggest improvements, or share your own analysis.
