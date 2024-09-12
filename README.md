
# Project Title: **Digital Screen Time and Well-being Analysis**

## Team Members:
- **Ayush Dutta**
- **Bibek Gyawali**
- **Subhash Shahu**

## Project Overview:
This project explores how digital screen time affects self-reported well-being among a large cohort of adolescents. We use data science techniques to analyze three datasets provided, investigating relationships between digital screen time, demographics, and well-being indicators.

### Datasets:
We have three datasets that contain demographic information, screen time usage, and well-being scores for over 100,000 adolescent respondents.

1. **dataset1.csv**: Demographic information.
   - **ID**: Unique respondent identifier
   - **gender**: Self-reported gender (1 for male, 0 otherwise)
   - **minority**: 0 for majority ethnic group, 1 for others
   - **deprived**: 1 if residing in areas with high deprivation indices, 0 otherwise

2. **dataset2.csv**: Daily screen time in hours.
   - **C_we**: Hours using computers on weekends
   - **C_wk**: Hours using computers on weekdays
   - **G_we**: Hours playing video games on weekends
   - **G_wk**: Hours playing video games on weekdays
   - **S_we**: Hours using a smartphone on weekends
   - **S_wk**: Hours using a smartphone on weekdays
   - **T_we**: Hours watching TV on weekends
   - **T_wk**: Hours watching TV on weekdays

3. **dataset3.csv**: Self-reported well-being indicators.
   - **Optm**: Feeling optimistic about the future
   - **Usef**: Feeling useful
   - **Relx**: Feeling relaxed
   - ... (see the full project description for all 14 well-being indicators)

Each respondent scored their well-being indicators on a scale from 1 (None of the time) to 5 (All of the time).

## Project Objectives:

### Objective 1: Descriptive Statistical Analysis
- **Analysis 1**: Investigate the distribution of screen time by gender and ethnicity.
- **Analysis 2**: Calculate the average well-being score for each gender and deprivation group.

### Objective 2: Inferential Statistical Analysis
- **Analysis 1**: Test if there’s a significant difference in well-being scores between high and low screen-time users.
- **Analysis 2**: Determine the correlation between different types of screen time (e.g., smartphone usage, TV watching) and well-being.

## Technologies Used:
- **Python**: Main programming language
- **Pandas**: For data manipulation and analysis
- **Matplotlib** & **Seaborn**: For data visualization
- **Scipy** & **Statsmodels**: For inferential statistics
- **Google Colab**: For collaborative coding and experimentation

## File Structure:
```
- datasets/
  - dataset1.csv
  - dataset2.csv
  - dataset3.csv
- analysis/
  - descriptive_analysis.ipynb
  - inferential_analysis.ipynb
- results/
  - figures/
    - screen_time_by_gender.png
    - wellbeing_by_screen_time.png
  - summary_statistics.csv
  - correlation_matrix.csv
- README.md
```

## Setup Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url
   cd your-repo-folder
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib statsmodels
   ```
3. Run the analysis notebooks:
   - Descriptive Analysis: Open `descriptive_analysis.ipynb` in Google Colab and run all cells.
   - Inferential Analysis: Open `inferential_analysis.ipynb` in Google Colab and run all cells.

## Results:
The key findings from the analysis include:
1. A significant relationship between screen time and well-being scores.
2. Gender and deprivation level are key factors in screen-time behavior and its impact on well-being.

## Future Work:
Further analysis could investigate specific well-being indicators to see how particular screen activities (e.g., gaming vs. smartphone use) correlate with mental health outcomes. Additionally, machine learning models can be developed to predict well-being based on screen time data.
