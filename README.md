# IPL Team & Player Performance Analysis

Exploratory data analysis of ball-by-ball IPL match data to uncover 
team and player performance trends across seasons.

## Dataset
Ball-by-ball IPL match dataset
- Columns: batting team, bowling team, batter, bowler, runs, wickets, venue, season, etc.

## What I Did
- Data Cleaning: null handling, duplicate detection, datetime parsing
- Top 10 run scorers and wicket takers across all IPL seasons
- Team-wise total runs comparison
- Strike Rate analysis (min. 500 balls faced) for reliable batting rankings
- Economy Rate analysis (min. 50 overs bowled) for reliable bowling rankings
- Powerplay vs Death Overs run distribution
- Orange Cap & Purple Cap holders identified per season
- Top IPL venues by matches hosted
- Interactive visualizations using Plotly Express

## Libraries Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Plotly Express

## How to Run
1. Download an IPL ball-by-ball dataset (e.g. from Kaggle)
2. Place the CSV file in the same folder as the notebook
3. Update the file path in the notebook if needed
4. Open `IPL_analysis.ipynb` in Jupyter Notebook or Google Colab
5. Run all cells

## Key Insights
- Mumbai Indians and CSK are among the strongest IPL teams
- Virat Kohli and Rohit Sharma are leading all-time run scorers
- Death overs contribute significantly more runs than Powerplay overs
- Strike rate is a more reliable performance metric than raw run count
