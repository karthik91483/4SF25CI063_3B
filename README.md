# Netflix Data Analysis – CIE 1

## Project Overview
This project analyzes the Netflix Movies and TV Shows dataset using Python, Pandas, NumPy, Matplotlib and Seaborn.

The notebook follows the same overall structure as the supplied Spotify CIE reference notebook: introduction, library imports, dataset loading, data understanding, missing-value analysis, cleaning and transformation, mean imputation, EDA, visualizations, insight generation and conclusion.

## Dataset
- File: `dataset/netflix_titles.csv`
- Records: 8,807
- Columns: 12

## Project Structure
```text
Netflix_CIE1_Reference_Project/
├── Netflix_CIE1_Analysis.ipynb
├── README.md
└── dataset/
    └── netflix_titles.csv
```

## Requirements
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Run in VS Code
1. Open this folder in VS Code.
2. Install the Python and Jupyter extensions.
3. Select a Python 3 kernel.
4. Open `Netflix_CIE1_Analysis.ipynb`.
5. Run all cells from top to bottom.

## Dataset-specific notes
The Netflix dataset does not contain Spotify fields such as popularity, danceability or energy. These analyses are replaced with Netflix-specific analysis of content type, release year, genres and duration. Movie duration (minutes) and TV-show duration (seasons) are treated separately.

Mean imputation is applied to suitable numerical duration values, grouped by content type. Missing dates are not mean-imputed because an artificial date would misrepresent the source data.
