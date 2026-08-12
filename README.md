# 🎬 Netflix Exploratory Data Analysis (EDA)

## 🔗 Project Resources

- **Google Colab Notebook:**  
  [https://colab.research.google.com/](https://colab.research.google.com/drive/1VqHYkLG9rKNT8a2XeL4VcDsEct3SINxd?usp=sharing)

- **Dataset:**  
   https://www.kaggle.com/datasets/shivamb/netflix-shows

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Netflix Titles dataset using Python. The objective is to understand the structure of the dataset, clean the data, visualize important trends, and extract meaningful business insights using Pandas, Matplotlib, and Seaborn.

---

## 📂 Dataset

- **Dataset:** Netflix Movies and TV Shows
- **Rows:** 8,807
- **Columns:** 12

### Features

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

# 📊 Project Workflow

### Step 1 – Data Loading & Inspection

- Loaded CSV dataset
- Checked dataset dimensions
- Examined data types
- Identified missing values
- Checked duplicate records
- Generated summary statistics

---

### Step 2 – Data Cleaning

Cleaning decisions made:

- Removed `show_id` as it is only a unique identifier.
- Converted `date_added` to datetime format.
- Preserved missing values in `director`, `cast`, and `country` columns to avoid introducing misleading information.
- Checked duplicate records.
- Created a `year_added` column from `date_added` for year-wise analysis.
- Verified data types.

---

### Step 3 – Exploratory Data Analysis

Business questions answered:

1. Which country has the most Netflix content?
2. Movies vs TV Shows — which is more common?
3. Which directors have the most titles?
4. How has Netflix content addition changed over time?
5. What is the distribution of movie durations?
6. Is there a relationship between a movie's release year and duration?

---

### Step 4 – Data Visualization

Visualizations created include:

- Bar Chart
- Pie Chart
- Horizontal Bar Chart
- Line Chart
- Histogram
- Scatter Plot
- Heatmap

---

# 📈 Key Findings

- The dataset contains 8,807 rows and 12 columns. Most columns have the object data type, while release_year is of type int64.
- The dataset contains missing values. The director column has the highest number of missing values (2,634), followed by the country and cast columns. A few missing values are also present in date_added, rating, and duration.
- No duplicate rows were found in the dataset.
- The show_id is related only to uniquely identifying each record. It does not contain meaningful information that helps analyze or predict characteristics of the content.
- The dataset contains information about both Movies and TV Shows, including details such as title, director, cast, country, release year, rating, duration, and description.

---

# 💡 Business Insights

- The United States has the highest number of Netflix titles in this dataset. This is visible in the Top 10 Countries bar chart, although titles listed under multiple countries are counted as combined entries.
- Movies form a larger share of Netflix content than TV Shows, as shown by the Movies vs TV Shows pie chart.
- The release-year analysis shows that 2019 has the highest number of titles in the dataset.
- Rajiv Chilaka appears as the director with the highest number of titles among non-missing director records, based on the Top 15 Directors chart.
- Most Netflix movies have a duration of 80–120 minutes, suggesting that this length is the most common choice for viewers.
- The sharp increase in Movies and TV Shows after 2016 shows that Netflix invested heavily in growing its content library.

---

# 📁 Project Structure

```
Netflix-EDA/
│
├── Netflix_EDA.ipynb
├── netflix_titles.csv
```

---

# 📚 Learning Outcomes

Through this project, I learned:

- Loading and inspecting datasets using Pandas
- Handling missing values effectively
- Performing data cleaning
- Working with datetime data
- Using `value_counts()`, `describe()`, `info()`, and other Pandas methods
- Creating meaningful visualizations with Matplotlib and Seaborn
- Choosing appropriate charts based on business questions
- Writing business insights from exploratory data analysis

---

# 👩‍💻 Author

**Vanshita Parab**

B.Tech Information Technology

Python | Data Analysis | Machine Learning | Full Stack Development

---

## ⭐ If you found this project helpful, consider giving it a star!
