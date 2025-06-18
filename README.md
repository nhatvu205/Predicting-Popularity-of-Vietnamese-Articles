# 📊 Predicting-Popularity-of-Vietnamese-Articles
This is the final project of 3 sophomores in the following courseworks: Pre-processing and Building Data, Machine Learning in Statistics of University of Information Technology - Vietnam National University (UIT - VNU).

This project aims to predict the **popularity level** of news articles from [VnExpress.net](https://vnexpress.net/) using machine learning regression models. By analyzing various features such as title, tags, publishing date, wordcount, number of images or videos (if available), category, and we forecast the potential engagement (comments and interactions in comment section) of an article.

---

## 👨‍💻 Team Members
- Vũ Đình Nhật - 23521104 - (https://github.com/nhatvu205)
- Hồ Huỳnh Thư Nhi - 23521107 - (https://github.com/its-Nhi-Ho)
- Lê Diễm Quỳnh Như - 23521122 - ()

---

## 📌 Objectives

- Automatically estimate article popularity before or shortly after publication.
- Provide insight for content creators and editors to optimize engagement.
- Experiment with multiple regression models and evaluate their effectiveness.

---

## 🚀 Features

- 🧹 Data collection via web scraping (BeautifulSoup & Selenium)
- 📊 Feature engineering from text and metadata, specifically from title, tags and date in our work
- 🤖 Regression models: Ridge Regression, Random Forest, XGBoost.
- 📈 Performance evaluation using  RMSE, R²

---

## 🧪 Dataset Description

We collected and processed ~5400 articles from VnExpress with the following attributes:

- `title`: Article headline
- `category`: News category
- `word_count`: Number of words
- `image_count`, `video_count`
- `date`
- `tags`
- `comments`, `interactions` *(target variables)*



