# 📊 Social Media Data Analysis with Python

This project focuses on simulating and analyzing social media tweet engagement using Python. It demonstrates core data science skills including data generation, cleaning, visualization, and statistical analysis using libraries like `pandas`, `numpy`, `seaborn`, and `matplotlib`.

---

## 🧠 Summary

Understanding what drives engagement on social media is key for creators and marketers. In this project, I explored patterns in tweet-like data to identify which categories (e.g., Fitness, Travel) receive the most user interaction, measured by likes.

---

## 🛠️ Approach

- Generated a dataset of 500 entries with random tweet dates, content categories, and like counts.
- Cleaned the data by:
  - Removing `null` and `duplicate` entries.
  - Converting fields (`Date`, `Likes`) to proper formats.
- Visualized:
  - A histogram of like distribution.
  - A boxplot comparing likes across content categories.
- Performed statistical analysis using `groupby()` and calculated category-wise average likes.

---

## ✅ Solution

By analyzing the cleaned data, I identified that **Fitness**, **Travel**, and **Health** categories had the highest average engagement. These insights can inform content strategy for better performance on social platforms.

---

## 📈 Results

- **Overall average likes**: ~4870  
- **Top categories by engagement**: Fitness, Travel, Health  
- **Tools used**: `pandas`, `numpy`, `seaborn`, `matplotlib`

Visuals include:
- 📊 Histogram showing like distribution
- 📦 Boxplot comparing category-wise likes

---

## 🙏 Acknowledgement

This project is inspired by the [Coursera Guided Project](https://www.coursera.org/learn/analyze-social-media-python/home/module/1) **"Clean and Analyze Social Media Usage Data with Python"**, which provided a strong foundation in data cleaning, exploration, and visualization using Python.

---

## 📁 Project Structure

```bash
├── README.md
├── social_media_analysis.ipynb
├── graphs/
│   ├── likes_histogram.png
│   └── category_boxplot.png
