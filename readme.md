## About This Project
This project studies movie data using Python in a Jupyter notebook.

Main goal:
- clean the raw movie data
- explore patterns in movies
- create simple visual charts
- find useful insights

## Tools and Libraries
The project uses:
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

### 1) Data Loading
- Loaded `movie.csv` into a DataFrame (`df`).
- Checked sample rows with `head()`.

### 2) Data Understanding
- Checked shape, columns, data types, and summary stats.
- Checked missing values.

### 3) Data Cleaning
- Converted `Release_Date` to datetime, then used year values for analysis.
- Removed extra spaces from `Genre`.
- Removed unnecessary columns:
  - `Overview`
  - `Poster_Url`
  - `Original_Language`
- Removed duplicate rows.
- Removed rows with missing values.

### 4) Feature Preparation
- Created rating groups from `Vote_Average` using categories (based on quartiles).

### 5) Exploratory Data Analysis (EDA)
- Count plot of movies by `Genre`.
- Count plot of movies by `Vote_Average` category.
- Histogram of movie release years.

