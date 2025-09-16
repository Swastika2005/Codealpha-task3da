📚 Exploratory Data Analysis on Books Dataset

This project performs data cleaning and visualization on a scraped books dataset. It focuses on book prices, showing distributions and identifying the most expensive books.

Features

✅ Clean price data from strings to numeric format

✅ Identify top 10 most expensive books

✅ Visualize price distribution with histogram + KDE

✅ Save cleaned dataset to a new CSV file

Installation

Make sure you have Python installed (3.8+) and then install the required libraries:

pip install pandas matplotlib seaborn

Usage

Place your dataset booksc.csv in the project folder.

Run the Python script:

python book_eda.py


The script will:

Clean the Price column

Display a bar chart of the top 10 most expensive books

Display a histogram with KDE of book prices

Save the cleaned data as cleanbooksc.csv

Example Visualizations

Top 10 Most Expensive Books – Bar chart showing book titles vs. price.

Distribution of Book Prices – Histogram with KDE showing frequency of prices.

Dataset

The CSV file should include columns like:

Title – Book title

Price – Book price (cleaned to numeric)

Availability – Stock availability

Rating – Book rating
