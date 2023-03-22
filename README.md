# Extract-stock-sentiments-from-news-headlines

# Overview
This Python code is designed to extract financial news headlines from HTML tables, parse and score them for sentiment using NLTK's VADER module, and plot the sentiment scores on a bar chart for analysis. The code utilizes various libraries including BeautifulSoup, Pandas, NLTK, and Matplotlib.

The code first extracts financial news headlines from HTML tables stored in the 'datasets' folder and stores the HTML tables in a dictionary. It then parses headlines from a single day and outputs them along with their corresponding time and date. Next, it iterates through all headlines and extracts the ticker, date, time, and headline text for each headline. It then uses NLTK's VADER module to analyze the sentiment of each headline and updates the lexicon with new words and values. The sentiment scores are plotted on a bar chart using Matplotlib.

The code also addresses issues with duplicates and weekend dates in the financial news headlines and filters them out accordingly. Finally, it selects a single trading day for a specific stock and visualizes the negative, neutral, and positive sentiment scores for that day on a stacked bar chart.

# Libraries Used
- BeautifulSoup
- Pandas
- NLTK's VADER module
- Matplotlib

# Steps
- Extract financial news headlines from HTML tables stored in the 'datasets' folder and store the HTML tables in a dictionary.
- Parse headlines from a single day and output them along with their corresponding time and date.
- Iterate through all headlines and extract the ticker, date, time, and headline text for each headline.
- Use NLTK's VADER module to analyze the sentiment of each headline and update the lexicon with new words and values.
- Plot the sentiment scores on a bar chart using Matplotlib.
- Filter out duplicates and weekend dates in the financial news headlines.
- Select a single trading day for a specific stock and visualize the negative, neutral, and positive sentiment scores for that day on a stacked bar chart.

<img width="722" alt="Screenshot 2023-03-22 at 2 11 22 PM" src="https://user-images.githubusercontent.com/49270107/227011955-b8af2f76-d98b-4dd4-b3c6-42e14c1a74f7.png">
