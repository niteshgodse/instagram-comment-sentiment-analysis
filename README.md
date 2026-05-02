# Instagram Comment Sentiment Analysis

## Overview
This project performs sentiment analysis on Instagram comments using Natural Language Processing (NLP). The goal is to understand audience engagement and perception by classifying comments into positive, negative, and neutral sentiments.

---

## Objective
- Gain hands-on experience with **data extraction from social media platforms**
- Perform **data cleaning and preprocessing** on unstructured text data
- Apply **Natural Language Processing (NLP)** techniques for sentiment classification
- Derive meaningful insights about **audience engagement and perception**


---

## Methodology

### 1. Data Collection**
Comments were collected from a personal Instagram post with over ~2000 comments. Initially, a Chrome extension (*IG Comments Exporter*) was used, but due to its limitation of extracting only ~200 comments, an alternative approach was adopted.
Using the browser’s **developer console** and JavaScript, comments were successfully extracted directly from the webpage.

### 2. Data Preparation**
The extracted data was saved and processed into a structured format (Excel).
Unnecessary elements such as duplicates, system-generated text (e.g., “reply”, “likes”), and noise were removed to obtain a clean dataset of **691 comments**.

### 3. Data Processing**
The cleaned dataset was imported into Python using libraries like **pandas**.
Basic preprocessing steps such as trimming text and handling missing values were performed.

### 4. Sentiment Analysis**
Sentiment analysis was applied using NLP techniques (TextBlob), where each comment was assigned a **sentiment score** and classified into:

* Positive
* Negative
* Neutral

### 5. Data Visualization**
The results were visualized using graphs (bar chart and pie chart) to understand the distribution of sentiments across all comments.

### 6. Insight Generation**
Based on the analysis, it was observed that most comments were neutral, while positive comments were significantly higher than negative ones. This indicates that the audience perception of the content is generally favorable.

---

## Results
- Majority of comments were **Neutral**
- Positive comments were higher than negative
- Indicates overall **favorable audience perception**

---

## Tech Stack
- Python
- Pandas
- Matplotlib / Seaborn
- TextBlob

---

## Project Structure
```
│
├── data/
├── notebooks/
├── images/
├── README.md
```

---

## Conclusion
This project demonstrates how sentiment analysis can be applied to social media data to gain insights into audience engagement and behavior.

---

## Future Improvements
- Use advanced NLP models (like VADER / BERT)
- Handle multilingual comments
- Build interactive dashboard

---

## Author
Nitesh Godse
