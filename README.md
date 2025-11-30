#  Netflix Data Analysis Project

##  Project Overview
This project is a comprehensive data analysis of the Netflix dataset, containing over 8,800 titles (movies and TV shows). The goal was to explore content trends, understand the platform's strategy shift towards original and international content, and visualize key insights using Python.
##  Data Source
The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows). It contains metadata for over 8,000 Netflix titles.
##  Key Insights & Features
* **Content Strategy:** Analyzed the ratio of Movies (approx. 70%) vs. TV Shows, revealing a strong focus on standalone films.
* **Global Expansion:** Identified top producing countries, highlighting major investments in **India** and **Japan** outside of the US.
* **Audience Targeting:** Confirmed a focus on mature audiences with **TV-MA** being the dominant rating.
* **Seasonal Trends:** Used a **Heatmap** to visualize content release patterns by month and year.
* **Content Themes:** Generated a **Word Cloud** to identify the most common keywords in title descriptions.
* **Top Talent:** Ranked the most frequent Directors and Actors on the platform.

##  Tech Stack
* **Python 3.x**
* **Pandas:** Data cleaning and manipulation.
* **Matplotlib & Seaborn:** Static and statistical data visualization.
* **WordCloud:** Text data visualization.
* **NumPy:** Numerical operations.

##  Project Structure
```text
├── netflix_titles.csv          # Raw Dataset
├── FULL NETFLIX DATA ANALYSIS.ipynb # Main Jupyter Notebook
├── README.md                   # Project Documentation
└── requirements.txt            # Required Python Libraries
```
##  How to Run
1.  **Clone the repository** (or download the files):
    ```bash
    git clone https://github.com/moix-hash/netflix-data-analysis.git
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the analysis:**
    Open `FULL NETFLIX DATA ANALYSIS.ipynb` in Jupyter Notebook or VS Code and run all cells.

##  Visualizations
*(Screenshots of the analysis)*

### 1. Global Content Heatmap
> A heatmap revealing the density of content added by month and year.
<img width="1044" height="549" alt="image" src="https://github.com/user-attachments/assets/1c7e8614-bcf9-4b61-bf19-fc14f6f49116" />


### 2. Content Ratings Distribution
> Breakdown of ratings (TV-MA, PG-13, etc.) showing the target demographic.
<img width="1169" height="549" alt="image" src="https://github.com/user-attachments/assets/1a903f09-f464-43f9-af5c-ef06038b0d31" />


### 3. Word Cloud
> Most frequent words found in Netflix movie descriptions.
<img width="1097" height="589" alt="image" src="https://github.com/user-attachments/assets/e68d43c7-c5d5-47ae-9df5-4d6d49385489" />


##  Conclusion
The analysis confirms Netflix's pivot from a US-centric distributor to a global content producer. The data shows a significant surge in content volume peaking in **2019**, with a clear strategy to capture international markets through localized production.

##  Author
* **Name:** Syed Moiz Shahab
* **LinkedIn:** [Syed Moiz Shahab](https://www.linkedin.com/in/syed-moiz-shahab-ab8560297/)
* **GitHub:** [moix-hash](https://github.com/moix-hash)


