# 📺 Netflix Data Analysis

This project performs an exploratory data analysis (EDA) on a dataset of Netflix titles. The goal is to uncover insights related to the types of content available on Netflix, trends over the years, and patterns in genre, ratings, and production countries.

## 📘 Contents of the Notebook

The notebook walks through:

1. **Loading and inspecting the dataset**
2. **Data cleaning**
   - Handling null values
   - Standardizing formats
3. **Exploratory Data Analysis (EDA)**
   - Type distribution (Movies vs TV Shows)
   - Country-wise production analysis
   - Temporal trends in content addition
   - Rating distributions
   - Duration breakdown
   - Genre (listed_in) frequency analysis
4. **Data Visualization**
   - Count plots, bar charts, heatmaps, and line plots using `seaborn` and `matplotlib`

## 🗂 Dataset

- **Source:** [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Columns include:**
  - `title`, `type`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

## 🛠 Tech Stack

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib

Install dependencies:

```bash
pip install pandas numpy seaborn matplotlib
```
📈 Sample Questions Answered
Which type of content is more common on Netflix?

What countries produce the most content?

What is the trend of new content being added over the years?

What are the most common ratings?

Which genres are most represented?

🧪 How to Run
Clone the repository or download the notebook:

bash```

git clone https://github.com/your-username/netflix-eda.git
cd netflix-eda
```
Install the required libraries:

bash```

pip install -r requirements.txt
```

📊 Sample Visualizations
📉 Line plot of content added over the years

📊 Bar plot of content types

🌍 Country-wise content distribution

🧱 Heatmap of missing data

💡 Insights
Movies dominate Netflix’s content library.

The US leads in content production.

Content addition peaked around 2019–2020.

TV Shows tend to be categorized with fewer genres per item compared to Movies.

📄 License
This project is licensed under the MIT License.


