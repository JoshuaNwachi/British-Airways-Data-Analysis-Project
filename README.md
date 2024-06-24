
# British Airways Data Science Project

## Project Overview
This project focuses on analyzing customer reviews and building a predictive model for customer bookings for British Airways. The project is divided into two main tasks:

1. **Sentiment Analysis of Customer Reviews**: Scraping and analyzing customer reviews from the Skytrax website to understand customer sentiment and identify common themes.
2. **Predictive Model for Customer Bookings**: Building a machine learning model to predict whether a customer will make a booking based on provided data.

## Data Collection and Cleaning

### Sentiment Analysis
- **Data Scraping**: Customer reviews were scraped from the Skytrax website using Python libraries such as `requests` and `BeautifulSoup`.
- **Data Cleaning**: The collected reviews were cleaned by removing HTML tags, punctuation, and normalizing the text.
- **Sentiment Analysis**: Three different models (VADER, TextBlob, and BERT) were used to analyze the sentiment of the reviews. The results were combined using a majority vote approach to ensure robust sentiment classification.
- **Additional Analysis**: Topic modeling and word clouds were created to identify common themes and frequent feedback points.
<img width="1012" alt="Screenshot 2024-06-23 at 20 04 14" src="https://github.com/JoshuaNwachi/British-Airways-Data-Analysis-Project/assets/43007969/c84d7782-66a5-4148-8fd2-440ff86cea4a">

### Predictive Model
- **Data Preparation**: The customer booking dataset was explored and prepared, including handling missing values, encoding categorical variables, and scaling numerical features. Feature engineering was performed to create new features for better model performance.
- **Model Training**: A RandomForestClassifier was trained to predict customer bookings. The model was optimized using GridSearchCV and evaluated with metrics such as F1 score , Precesion and Recall.
- **Feature Importance**: Analyzed the importance of each feature to understand which factors most influenced booking decisions.
<img width="980" alt="Screenshot 2024-06-23 at 20 04 28" src="https://github.com/JoshuaNwachi/British-Airways-Data-Analysis-Project/assets/43007969/dda3445b-294b-4649-a3e4-361e6380a1b7">

## Notebooks
- **British_Airways_Sentiment_Analysis_task.ipynb**: Contains the complete workflow for scraping, cleaning, and analyzing customer reviews.
- **Predictive_Model.ipynb**: Includes the data exploration, preparation, and training of the predictive model for customer bookings.
- **Web Scraping.ipynb**: Initial notebook provided for dataset exploration and basic statistics.

## Results and Impact
- **Sentiment Analysis**: Provided insights into customer perceptions, helping British Airways identify strengths and areas for improvement in their services.
- **Predictive Model**: Offered actionable insights into customer booking behavior, enabling more effective marketing strategies and improving operational efficiency.
- Overall, the project enabled British Airways to make data-driven decisions to better understand and serve their customers.

