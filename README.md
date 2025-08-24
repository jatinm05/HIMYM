# How I Met Your Mother Episode Analysis

This project explores the *How I Met Your Mother* dataset, analyzing episodes across all nine seasons. It includes exploratory data analysis, visualization, and predictive modeling of IMDB ratings.

## Dataset
The dataset contains information about each episode, including:
- Season and Episode number
- Title
- IMDB Rating
- Number of Votes
- US Viewership

## Analysis and Visualizations
1. **Season-wise Trends**  
   - Line plots for each season showing episode-wise IMDB ratings.
   - Combined plot comparing ratings across all nine seasons.

2. **Distribution Analysis**  
   - Histograms and boxplots of IMDB ratings.
   - Viewer distribution across seasons.
   - Correlation heatmap of numerical features.

3. **Episode Insights**  
   - Highest and lowest-rated episodes.
   - Episodes with the most votes.
   - Relationship between viewership and ratings.

## Machine Learning Models
Built regression models to predict IMDB ratings based on season, episode, votes, and viewership:
- **Linear Regression** (R² ≈ -0.18, not a good fit)
- **Random Forest Regressor** (R² ≈ 0.43, better performance)
