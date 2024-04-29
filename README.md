# E-Commerce-Data-Analysis
This Python script is designed to analyze an e-commerce dataset containing information about fashion products. The analysis includes data visualization, text classification, and additional text analysis.

## Dataset Information

The dataset is loaded from a JSON file named 'fashion_products_dataset.json'.
Basic information about the dataset is displayed using df.info().
## Data Visualization
Missing Values Heatmap:
Visualizes missing values in the dataset using a heatmap.
Distribution of Products across Categories:
Displays the distribution of products across different categories using a count plot.
Distribution of Products across Top 20 Brands:
Shows the distribution of products across the top 20 brands using a count plot.
Pricing Trends and Discount Strategies:
Distribution of actual prices is visualized using a histogram.
Distribution of discounts is visualized using a histogram.
Distribution of Average Ratings:
Displays the distribution of average ratings using a count plot.

## Text Classification
Text classification is performed to predict if a product is out of stock (out_of_stock is assumed as the target variable).
Text data from the 'description' column is used for classification.
The dataset is split into training and testing sets.
Text vectorization is performed using TF-IDF.
Multinomial Naive Bayes classifier is used for text classification.
The classification report and accuracy score are displayed.

## Word Cloud for Sentiment Analysis
Word clouds are generated for products that are out of stock and products that are in stock.
Word frequency analysis is also performed to identify the top 20 words by frequency in product descriptions.

## Libraries Used
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
WordCloud
