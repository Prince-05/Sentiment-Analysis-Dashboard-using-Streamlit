# Sentiment Analysis of Tweets about US Airlines

This project is a Streamlit dashboard for analyzing the sentiments of tweets related to US airlines. The application provides visualizations and insights into the data, including sentiment distribution, word clouds, and more.

## Features

- Display random tweets based on sentiment (positive, neutral, or negative).
- Visualize the number of tweets by sentiment using bar plots or pie charts.
- Explore tweet locations and time of activity.
- Analyze the total number of tweets for each airline.
- Breakdown of airline sentiments with multi-airline comparisons.
- Generate word clouds for tweets of specific sentiments.

## Prerequisites

Ensure you have the following installed:

- Python 3.8 or later
- Required Python libraries:
  - `streamlit`
  - `pandas`
  - `numpy`
  - `plotly`
  - `wordcloud`
  - `matplotlib`

Install the dependencies using pip:

```bash
pip install streamlit pandas numpy plotly wordcloud matplotlib
```

## Dataset

The application uses a CSV file named `Tweets.csv`, which contains the following columns:

- `text`: The content of the tweet.
- `airline`: The airline associated with the tweet.
- `airline_sentiment`: The sentiment of the tweet (positive, neutral, or negative).
- `tweet_created`: The timestamp of the tweet.

Ensure the dataset is located at the path specified in the code:


Update this path in the script if your dataset is stored elsewhere.

## How to Run

1. Clone this repository or save the Python script to your local machine.
2. Open a terminal and navigate to the directory containing the script.
3. Run the Streamlit app:

```bash
streamlit run your_script_name.py
```

Replace `your_script_name.py` with the name of the script file.

4. Open the URL provided by Streamlit (e.g., `http://localhost:8501`) in your web browser.

## Application Sections

### 1. Random Tweet
- Displays a random tweet based on the selected sentiment.

### 2. Number of Tweets by Sentiment
- Visualize sentiment distribution using bar plots or pie charts.

### 3. Tweet Locations by Time
- Filter tweets by the hour of the day and visualize locations on a map.

### 4. Total Number of Tweets per Airline
- Compare the total number of tweets for each airline using bar plots or pie charts.

### 5. Breakdown by Sentiment
- Analyze sentiment breakdown for selected airlines using bar plots or pie charts.

### 6. Word Cloud
- Generate a word cloud for tweets with a specific sentiment.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or new features.

## License

This project is licensed under the MIT License. Feel free to use and modify it.

## Acknowledgments

- Thanks to Streamlit for providing an easy-to-use framework for building interactive web apps.
- The dataset is sourced from public repositories for educational purposes.

