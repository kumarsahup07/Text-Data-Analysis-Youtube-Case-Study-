# 📺 YouTube Comments Analysis Project

Completed a hands-on project using Pandas, TextBlob, Seaborn & Matplotlib for natural language processing (NLP), emoji frequency analysis, and user engagement insights on YouTube comment data.  

![YouTube Comments Dashboard](https://raw.githubusercontent.com/your-username/your-repo/main/your-image-name.png)

---
##  Data Collection
- Dataset Source - [G-drive](https://drive.google.com/drive/folders/1makDwgfKzmqOSikEnOLkmMskT3609dAo)
---
## **Overview**  
This project dives into YouTube video comment data to perform sentiment analysis, emoji analysis, and audience engagement scoring across various video categories. It reveals viewer emotions, popular emojis, and categories with the most engagement.

---

## **Sample Data**

| video_id       | comment_text                          | likes | replies |
|----------------|---------------------------------------|-------|---------|
| XpVt6Z1Gjjo    | Logan Paul it's yo big day ‼️‼️‼️     | 4     | 0       |
| XpVt6Z1Gjjo    | I've been following you from the start| 3     | 0       |
| sjlHnJvXdQs    | This is priceless                     | 0     | 0       |
| 8wNr-NQImFg    | BEN CARSON IS THE MAN!!!!!            | 0     | 0       |
| vu_9muoxT50    | WTF BRUH!!!!!!                        | 0     | 0       |

---

## **Objectives**  
- Analyze sentiment polarity of comments.  
- Identify and count emoji usage frequency.  
- Map video category names using category ID.  
- Explore trends across audience engagement.  
- Visualize patterns in user responses across different genres.

---

## **Data Processing**  
- Loaded and merged multiple CSVs from the YouTube dataset.  
- Cleaned null values and standardized comment fields.  
- Converted emojis to frequency counts and extracted top 10.  
- Calculated polarity using `TextBlob`.  
- Handled mixed data types with explicit dtype casting.  

---

## **Key Insights**  
- **Top Emojis:** 😂, 😍, ❤, 🔥 dominate viewer expressions.  
- **Neutral Sentiment:** Most comments have polarity close to 0.  
- **Top Liked Categories:** Identified via grouping and `.sort_values()`  
- **Engagement Analysis:** Performed with comment frequency and likes.  

---

## **Visualizations**  
- 📊 Bar Plot of Most Used Emojis  
- ☁️ WordCloud of Comment Text  
- 📈 Sentiment Distribution Histogram  
- 📂 Category-wise Grouping and Analysis  

---

## **Technologies Used**  
- **Python:** Data wrangling and preprocessing  
- **Pandas:** DataFrame manipulation and merging  
- **TextBlob:** Sentiment polarity and subjectivity  
- **Seaborn & Matplotlib:** Advanced plotting  
- **Emoji:** Extraction and counting of emojis from comments  

---

## **Tutorial Breakdown**

1. 📂 How to Read CSV Data or Load Data – 11 min  
2. 🧠 Performing Sentiment Analysis – 11 min  
3. ☁️ WordCloud Analysis – 11 min  
4. 🎭 Emoji Analysis – 12 min  
5. 📥 Collect and Merge YouTube Data – 11 min  
6. 🗃️ Export to CSV/JSON/Databases – 12 min  
7. 💖 Analyzing the Most Liked Category – 13 min  
8. 🔄 Audience Engagement Analysis – 9 min  
9. 🔥 Analyzing Trending Videos – 7 min  
10. ❓ Do Punctuations Affect Views – under review  

---

## **Author**  
- **Priyanshu Kumar Sahu** – [GitHub Profile](https://github.com/kumarsahup07)

---
