# Game-Time

## Video Game Analysis
**Video Game Analysis Using RAWG Dataset**

## People and Responsibilities
- **Mohammad Javad Farokhi Darani**: Data collection, data preprocessing, analysis, and visualization.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/mjavadf/gametime/blob/main/LICENSE) file for details.

## Description
This project analyzes video game data from the RAWG database, exploring trends in game genres and platforms over the decades. The RAWG dataset includes detailed information on games, such as their release dates, genres, and platforms.

### Datasets
- The `rawg` dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/jummyegg/rawg-game-dataset).
- The `rawg_by_metric` is scraped from [RAWG database](https://api.rawg.io/docs/)
- The `vgsales` datas is sourced from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)

### Analysis
The analysis focuses on answering these questions:
- What are the most popular game genres in each decade, and how has this changed over time?
- Are there any genres that are exclusive to specific platforms?
- Can we identify trends or patterns in the rise and fall of different genres?

## Installation
To install the necessary dependencies, run the following command:
```bash
pip install pandas matplotlib numpy plotnine
```

## Usage
To reproduce the analysis, run the provided Jupyter notebook. The notebook includes detailed steps for data preprocessing, analysis, and visualization.

## Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mjavadf/gametime/HEAD?filepath=game_time.ipynb)