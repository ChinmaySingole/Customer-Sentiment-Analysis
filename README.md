
# Customer Sentiment Analysis

## Objective

The primary objective of this project is to gauge customer sentiment towards the iPhone 15 128GB model by analyzing product reviews from Flipkart. The analysis aims to extract insights about public perception, identify key concerns and positive highlights, and provide recommendations for improving customer experience and marketing strategies.

## Project Overview

This project aims to analyze customer sentiment towards the iPhone 15 128GB model by scraping and processing product reviews from Flipkart. By performing sentiment analysis on customer reviews, we derive insights into public perception, which can be useful for decision-making, improving customer experience, and identifying key areas for product improvement.


## Tools and Libraries Used

- Selenium (Automated web scraping)

- BeautifulSoup (HTML parsing and data extraction)

- Pandas (Data cleaning, processing, and analysis)

- TextBlob (Sentiment analysis)

- Matplotlib & Seaborn (Data visualization)

## Project Analysis Steps:

### 1. Data Collection (Web Scraping)

- Used Selenium to navigate Flipkart's product page and scrape at least 300 reviews.

- Extracted review details (username, rating, and review text) using BeautifulSoup.

- Handled pagination to gather reviews from multiple pages.

### 2. Data Cleaning and Preprocessing

- Removed duplicate and missing values.

- Converted review text to lowercase, removed special characters, and tokenized text.

- Removed stop words and applied lemmatization to normalize text.

### 3. Sentiment Analysis

- Used TextBlob to analyze sentiment polarity (-1 to +1) and subjectivity.

- Classified reviews as:

   - Positive: Polarity score ≥ 0.1

   - Negative: Polarity score < 0.1

### 4. Data Analysis and Insights

- Sentiment Distribution: Analyzed overall sentiment percentages.

- Average Rating vs Sentiment: Checked correlation between review ratings and sentiment scores.

- Word Cloud: Identified frequently mentioned words in positive and negative reviews.

- Review Length Analysis: Explored if longer reviews provide stronger sentiment.

### 5. Reporting

- Summarized key findings from the sentiment analysis.

- Identified common issues and highlights based on customer reviews.

- Suggested improvements for the iPhone 15 128GB model and potential marketing strategies for Flipkart.
## Usage

1. Clone the repository:
```bash
  git clone https://github.com/ChinmaySingole/Customer-Sentiment-Analysis.git
```
    
2. Install dependencies:
```bash
pip install selenium beautifulsoup4 pandas textblob matplotlib seaborn
```
3. Open the Jupyter Notebook:
```bash
jupyter notebook "Project.ipynb"
```
4. Run the notebook cells to train the model and make predictions.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.