![MasterHead](https://cdn.dribbble.com/users/1197989/screenshots/5585685/media/139eef797b4034c31cd8189a717c2022.gif)

# Swiggy - Sentiment Analysis and Sales Forecasting
Swiggy Anaysis (bangalore) based on Data Scrapped from website.

---

## Aim of the project 🎯:

The aim of this project is to empower Swiggy and its partnering restaurants with actionable insights by leveraging sentiment analysis and time-series forecasting techniques. By analyzing customer reviews and order data, the project seeks to predict future sales trends and understand customer satisfaction levels. This data-driven approach aims to optimize restaurant strategies, enhance customer experiences, and support informed decision-making to drive growth in the highly competitive food delivery market.

---

## Project Description 📃:

In this project, we dive deep into Swiggy’s ecosystem, combining Natural Language Processing (NLP), Machine Learning, and advanced analytics to extract meaningful insights from customer feedback and predict future demand.

Project Phases:

- Data Extraction and Cleaning:
  - Scraped and collected real-time customer review data, order history, and restaurant information.
  - Utilized Python libraries such as Pandas, BeautifulSoup, and Requests for extraction and initial processing.
  - Cleaned and transformed the data using advanced Excel functions and Python to remove null values, fix formatting inconsistencies, and structure it for analysis.

- Sentiment Analysis using NLP:
  - Built an NLP model using libraries like NLTK and TextBlob to classify customer reviews into Positive, Negative, and Neutral categories.
  - Achieved a sentiment classification accuracy of over 85%, enabling deeper understanding of customer satisfaction patterns across different restaurants and areas.

- Sales Forecasting with Time Series Modeling:
  - Applied time-series forecasting models (ARIMA, Prophet) to predict future food delivery demand.
  - Achieved a forecasting accuracy of 95%, providing critical insights into expected order volumes during peak seasons and normal periods.

- Data Visualization using Power BI:
  - Created dynamic dashboards to visualize sentiment trends, popular cuisines, customer satisfaction by area, and forecasted sales.
  - Integrated slicers for area-wise, cuisine-wise, and sentiment-wise exploration to enhance interactivity.

---

# _Steps involved in process:_

## 1. Data Cleaning 🧹

1. Handling Duplicates and Nulls: Removed duplicates and cleaned missing values to maintain high-quality data.
2. Standardization: Standardized formats for dates, ratings, review texts, and restaurant names.
3. Sentiment Labeling: Annotated review texts with sentiment labels (Positive, Negative, Neutral) for downstream analysis.

## 2. Sentiment Analysis 📈

1. Used Natural Language Processing (NLP) techniques to classify customer reviews based on sentiment.
2. Identified trends in customer emotions, common grievances, and factors contributing to positive dining experiences.

## 3. Sales Forecasting 📊

1. Modeled historical order data using ARIMA and Facebook Prophet.
2. Predicted future order volumes and revenue trends, highlighting expected demand spikes, low seasons, and growth areas.
3. Generated actionable timelines for marketing campaigns and capacity planning.

## 4. Insights Generated 📊

1. A detailed examination of the mean price of food items across different cities was conducted. The study focused on prominent cities such as Mumbai, Bangalore,Delhi and other cities, revealing significant insights into the pricing patterns and cost dynamics of the local food industry.
![image]((https://github.com/KunalChopkar07/swiggy---sentiment-analysis-and-sales-forecasting/issues/1#issuecomment-2834255561))

2. In the analysis of Swiggy data, notably Indiranagar and BTM Layout were offering most expensive dishes, whereas the base the price for all of the areas was the same.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/b1d1726b-6270-4be4-a0fe-eecc5f196053)

3. A focus was placed on determining the popularity of different areas based on the number of ratings received by restaurants. Specifically, restaurants with more than 1000 ratings were considered significant indicators of popularity. Through this analysis, several areas emerged as the most popular hubs for dining experiences.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/687b7052-54ec-48ae-b709-ab811866adc2)

4. A correlation study was conducted to explore the relationship between restaurant ratings and delivery times. Surprisingly, the findings revealed a negative correlation between these two variables. This means that, contrary to common expectations, as delivery times increased, restaurant ratings tended to decrease.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/99433bc8-9029-46ae-a360-a1f586de44c5)

5. A specific focus was placed on identifying areas with the highest number of low-rated restaurants, considering ratings below 3.5 as indicators of low customer satisfaction. This criterion allowed for a detailed examination of areas where diners might face disappointing dining experiences.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/d72b3ac3-100c-4f46-a7b9-1bbef86f0a16)

6. A comprehensive examination was conducted to understand the culinary landscape in different areas. The focus was on identifying the most popular cuisines and their distribution across various regions. Interestingly, the research revealed that a select few cuisines dominated the market, with the top 5-6 cuisines collectively constituting more than half of the total market share.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/0b46d2ae-6122-414f-a1da-73c5c411f541)

7. The Swiggy dashboard offers a user-friendly interface providing insights, highlighting areas with low-rated restaurants, and offering detailed cuisine price information. The addition of the area-wise slicer enhances user interactivity, ensuring a personalized and data-driven decision for entity.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/29bb707e-6924-4d3c-b669-f39eff5cb2f6)

