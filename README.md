# 📊 Udemy Courses Analysis

This project performs an in-depth Exploratory Data Analysis (EDA) on a Udemy course dataset. It uncovers insights about pricing, course levels, popularity, and subject distribution, using Python's data science ecosystem.

The analysis is done in a Jupyter Notebook and includes visualizations to help understand the structure and trends within the dataset.

---

## 📌 Objectives

- Load and inspect Udemy course data
- Clean and prepare the dataset (handle nulls, duplicates, date conversion)
- Compare free vs paid courses
- Analyze number of lectures, reviews, and subscribers
- Explore subject popularity and course levels
- Visualize key distributions and relationships
- Identify top courses by engagement

---

## 🛠️ Tools & Libraries

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

---

## 🗂️ Dataset Features

- **course_title**: Course name
- **url**: Course link
- **is_paid**: Paid or Free
- **price**: Course price
- **num_subscribers**: Number of students enrolled
- **num_reviews**: Number of reviews
- **num_lectures**: Total number of lectures
- **level**: Course difficulty (Beginner, Intermediate, etc.)
- **content_duration**: Duration in hours
- **subject**: Main subject area (e.g., Web Development, Business)
- **published_timestamp**: Date course was published

---

## 🔍 Key Steps Performed

1. **Data Loading**
   - Read CSV data and preview top/bottom rows
   - Check dataset structure and types

2. **Data Cleaning**
   - Converted `published_timestamp` to datetime
   - Handled missing values and duplicates

3. **Exploratory Analysis**
   - Counted number of courses per subject and level
   - Compared paid vs free courses (counts, lectures, popularity)
   - Sorted courses by number of subscribers
   - Filtered free high-rated and most subscribed courses

4. **Visualizations**
   - Used bar plots and count plots to compare categories
   - Displayed relationships between variables using seaborn and matplotlib

---

## 📈 Insights

- 💼 **Business** and 💻 **Web Development** are the most common subjects.
- 🆓 Free courses are highly subscribed but often shorter in content.
- 🧑‍🎓 Beginner-level courses dominate the platform.
- 💬 Courses with high review counts usually have higher enrollments.
- 💸 Paid courses tend to have more content (lectures and duration).

---
