# 📊 Udemy Course Data Analysis Using Pandas

This project explores and analyzes a dataset of Udemy online courses using Python libraries like **Pandas**, **Matplotlib**, and **Seaborn**. The aim is to understand trends in pricing, subject popularity, enrollment numbers, and more.

---

## 📁 Dataset

The dataset typically includes the following columns:

- `course_id`: Unique ID of the course
- `course_title`: Title of the course
- `subject`: Subject category (e.g., Business, Web Development, etc.)
- `price`: Price of the course (in USD)
- `num_subscribers`: Total number of subscribers
- `num_reviews`: Number of reviews
- `num_lectures`: Number of lectures
- `level`: Difficulty level (e.g., Beginner, Intermediate, Expert)
- `content_duration`: Total course duration (in hours)
- `published_timestamp`: Date when the course was published

A sample Udemy dataset is available on [Kaggle](https://www.kaggle.com).

---

## 🎯 Objectives

- Explore the most popular subjects on Udemy
- Analyze pricing patterns for different course levels and topics
- Investigate which types of courses attract the most students
- Visualize trends over time in course publication
- Detect potential correlations (e.g., price vs. subscribers)

---

## 🛠️ Tools & Libraries Used

- **Python 3**
- **Pandas** for data wrangling
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebook** for interactive analysis

---

## 🧪 Project Workflow

1. **Load Dataset**
   ```python
   import pandas as pd
   df = pd.read_csv('udemy_courses.csv')
