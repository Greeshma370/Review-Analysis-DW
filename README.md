📌 Project Overview

This project involves cleaning, processing, and analyzing a dataset of Amazon product reviews. The dataset contains various attributes such as product details, reviews, ratings, and timestamps. The goal was to handle missing values, format data correctly, and prepare it for further analysis or visualization.

📂 Dataset Details

The dataset consists of 1,597 rows and 27 columns, including:

Product Information: id, asins, brand, categories, manufacturer

Review Details: reviews.text, reviews.title, reviews.username, reviews.rating

Metadata: dateAdded, dateUpdated, prices, upc, ean

🛠️ Data Cleaning Steps

Handled Missing Values: Identified and managed NaN values in colors, reviews.username, reviews.userCity, etc.

Fixed Date Formatting Issues: Converted dateAdded and dateUpdated into a standardized datetime format.

Column Selection & Formatting: Ensured necessary columns were kept and formatted correctly.

Checked for Duplicates: Removed duplicate entries to maintain data integrity.

📊 Potential Further Analysis

Sentiment Analysis: Analyze review text to determine customer sentiments.

Price Trends: Study price fluctuations over time.

Brand-Wise Review Analysis: Compare ratings and review trends among different brands.
