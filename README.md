# Books-Price-Monitoring-and-Sentiment-Analysis
This project introduces an intelligent Python-based system that automates the extraction, 
monitoring, and analysis of book prices and customer sentiments from an online bookstore. By 
integrating web scraping, sentiment classification, data visualization, and an interactive menu
driven interface, the solution provides real-time insights into book pricing and reader 
satisfaction. The tool simplifies decision-making for readers and book enthusiasts by offering 
a centralized way for sentiment-rich book exploration. 

🚀 Project Goals

🔍 Monitor book prices from an e-commerce platform (e.g., books.toscrape.com)

💬 Collect and analyze user reviews using sentiment analysis

📉 Track price fluctuations over time

📊 Visualize data trends using plots

🧠 Use machine learning models for review classification

📘 Sentiment Analysis Overview

This project utilizes Natural Language Processing (NLP) techniques to analyze user reviews of books. Using TextBlob, we compute sentiment polarity scores from review texts to classify them as positive, negative, or neutral. Additionally, star ratings (1–5) are mapped to sentiment labels to support weak supervision. For machine learning-based sentiment classification, TF-IDF is applied to convert textual data into feature vectors, and a RandomForestClassifier is trained on this transformed data to accurately predict the sentiment of new reviews. This combination of lexical and ML-based methods provides robust insights into reader opinions.
