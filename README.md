✈️ British Airways Data Science Project

📚 Background Information

📌 Task 1: Customer Feedback Analysis

British Airways (BA) operates thousands of flights daily across the world. Understanding customer feedback is crucial to improving service quality. This task focuses on scraping and analyzing customer reviews to extract insights and enhance customer satisfaction.

📌 Task 2: Customer Booking Prediction Model

In a competitive airline market, predicting customer behavior is essential. This task involves building a predictive model using booking data to identify whether a customer will purchase a holiday, helping BA make data-driven decisions.

📂 Dataset Information

Task 1 Dataset (Customer Feedback)

Source: Web-scraped from airlinequality.com

Key Columns:

reviews: Raw customer reviews

Cleaned Reviews: Processed text

Sentiment: Sentiment score (Positive, Negative, Neutral)

Task 2 Dataset (Customer Booking Data)

Source: Customer booking records

Goal: Predict holiday purchase (Yes/No)

🔍 Key Tasks Performed

Task 1: Customer Feedback Analysis

Data Collection: Web scraping with BeautifulSoup.

Data Cleaning: Removing noise, tokenization, and stopword removal.

Sentiment Analysis: Using VADER to classify reviews into positive, negative, or neutral.

Visualization: Pie charts for sentiment distribution and word clouds for common terms.

Task 2: Customer Booking Prediction Model

Data Preprocessing: Handling missing data and encoding categorical variables.

Model Building: Training models like Logistic Regression and Random Forest.

Evaluation: Measuring performance with accuracy, precision, recall, and F1-score.

📈 Results and Insights

Task 1: Sentiment Analysis

Positive: 45.8% of reviews

Negative: 42.8% of reviews

Neutral: 11.4% of reviews

Insights:

Negative reviews often mention delays and poor service.

Positive reviews highlight premium class comfort.

Task 2: Predictive Model

Model Accuracy: 87%

Key Predictors: Age, location, booking lead time, and travel class.

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/british-airways-analysis.git
cd british-airways-analysis

Install dependencies:

pip install -r requirements.txt

Run the analysis:

python main.py

📊 Output

BritishAirways_review.csv: Cleaned dataset

Sentiment pie chart

Word cloud

Model performance report

📌 Future Improvements

Use advanced models (e.g., BERT) for sentiment analysis.

Perform topic modeling for deeper insights.

Optimize the prediction model with hyperparameter tuning.

🤝 Contribution

Contributions are welcome! Fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License.

