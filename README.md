
# Netflix Case Study

## Project Objective

To explore and analyze Netflix’s content catalog using real-world data to uncover insights about content types, genres, countries, release trends, and key contributors (actors, directors). The goal is to understand how Netflix structures its content globally and how its offerings have evolved over time.

##  What This Project Does

- Loads and cleans the Netflix dataset
- Handles missing values and transforms columns (e.g., date extraction)
- Performs Exploratory Data Analysis (EDA)
  - Movie vs TV Show distribution
  - Top genres, countries, durations
  - Content addition trends over years and months
  - Most frequent actors
- Visualizes insights using bar plots, histograms, and word clouds
- Summarizes key takeaways and possible next steps

##  Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- WordCloud
- Jupyter Notebook

## Dataset

This project relies on the [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) dataset compiled by Kaggle user **Shivam Bansal**. The data contains Netflix's public catalogue listings and is made available under the **CC0: Public Domain** license. Netflix retains ownership of the original content information. If the Google Drive link below is unavailable, you can download the CSV directly from Kaggle. With the `kaggle` command-line tool run:

```bash
kaggle datasets download -d shivamb/netflix-shows -f netflix_title.csv
```

A Kaggle account and API token are required.

## Setup

1. Download **netflix_title.csv** from [Google Drive](https://drive.google.com/uc?export=download&id=1-qDO7oNwzQn0RV44YtpqWdYS4SO3GkQg) or from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and place it in this project folder.
2. Install dependencies (requires **Python 3.10**):

   ```bash
   pip install -r requirements.txt
   ```

## Quick Start

To quickly launch the notebook in a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook Netflix_Case_Study.ipynb
```

##  Why This Matters

This project helps understand user content preferences and trends, which are essential for:
- Business decision-making in content acquisition
- Product design and regional personalization

## Status

Completed

---

> Created by **Sarath**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

### Tags  
`#netflix` `#eda` `#data-analysis` `#python` `#pandas` `#seaborn` `#portfolio-project`
