Data Analytics Intermediate Project
# 📱 Social Media Sentiment Analysis | Twitter Airline Tweets

This project performs sentiment analysis on a dataset of 14,000+ tweets about major US airlines. Using **Natural Language Processing (NLP)**, we clean and analyze the tweets to identify whether they express **positive**, **negative**, or **neutral** sentiment, and visualize key patterns.

---

## 🎯 Objective

The goal of this project is to:
- Analyze public opinion on airlines based on Twitter data
- Classify tweets into positive, negative, and neutral categories
- Visualize trends and highlight common keywords in each sentiment

---

## 📁 Dataset

**Source:** [Twitter US Airline Sentiment – Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)

**Key columns:**
- `text`: The tweet content
- `airline_sentiment`: Sentiment label (`positive`, `negative`, `neutral`)
- `airline`: Airline mentioned

---

## 🛠 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- `pandas` – Data manipulation
- `matplotlib`, `seaborn` – Data visualization
- `nltk` – Text preprocessing (stopwords removal)
- `wordcloud` – Word visualization

---

## 📊 Steps Performed

1. **Data Loading & Exploration**
   - Read CSV file and check data structure
   - Inspect sentiment distribution

2. **Text Cleaning**
   - Lowercasing
   - Removing URLs, mentions, hashtags
   - Removing punctuation & stopwords

3. **Visualization**
   - Sentiment distribution plot using Seaborn
   - Word clouds for positive, negative, and neutral tweets
   - Most common words per sentiment

---

## 📈 Results

- The dataset contains more **negative tweets** than positive or neutral
- Common words in negative tweets reflect dissatisfaction with delays, customer service, and cancellations
- Positive tweets often mention helpful staff and good flight experiences
- Neutral tweets are mainly factual statements without strong emotion

---

## 🚀 Future Work

- Build a Machine Learning classifier to predict sentiment for new tweets
- Perform hashtag analysis for trending topics
- Apply the project to real-time Twitter data using the Twitter API

---

## 🤝 Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

---

## 📄 License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

---

## 👩‍💻 Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)
