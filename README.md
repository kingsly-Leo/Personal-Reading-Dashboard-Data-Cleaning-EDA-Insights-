# Personal-Reading-Dashboard-Data-Cleaning-EDA-Insights

This project focuses on analyzing a comprehensive books dataset to better understand personal reading patterns, book characteristics, and user preferences. It combines data cleaning, exploratory data analysis, and insightful visualizations to create a foundation for a personalized reading dashboard.

The goal of the project is to transform raw book data into meaningful insights—helping readers track habits, discover trends, and make informed reading choices.

📌 Overview

The dataset includes detailed information such as:

Book titles and IDs

Authors

Ratings (1–5 star distributions)

Total number of reviews

Page counts

Publication timeline (year, month, day)

Language and publisher details

ISBN information

This project processes these features to build a structured, insight-rich personal reading dashboard.

✨ Key Features

Data loading and preprocessing

Handling missing values and duplicates

Exploratory Data Analysis (EDA) to identify:

Favorite authors

Rating patterns

Page count distributions

Publishing trends

Popular languages and publishers

Visualizations using Python libraries

Summary of reading-related insights

🛠️ Technology Stack

Python

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualizations

Jupyter Notebook – Analysis environment

📂 Project Structure
personal-reading-dashboard/
│
├── data/
│   └── books.csv
│
├── notebooks/
│   └── reading_dashboard_analysis.ipynb
│
├── scripts/
│   ├── preprocess.py
│   └── visualize.py
│
├── README.md
└── requirements.txt


(Adjust according to your actual folder structure.)

📊 Insights Generated

Most-read or highest-rated authors

Page count trends across books

Year-wise publishing patterns

Rating distributions (1–5 stars)

Relationship between pages and ratings

Most active genres or languages (if included)

Identification of outliers or rare books

These insights form the core of the Personal Reading Dashboard, enabling clear understanding of reading behavior.

▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/personal-reading-dashboard.git
cd personal-reading-dashboard

2. Install Dependencies
pip install -r requirements.txt

3. Launch Jupyter Notebook
jupyter notebook


Open the notebook in the notebooks/ directory to view the complete analysis.

📌 Future Enhancements

Build an interactive dashboard in Power BI or Streamlit

Add a reading log (pages per day) to track reading habits

Create a recommendation engine based on favorite authors or genres

Perform clustering to group similar books

Add NLP-based sentiment analysis from book reviews
