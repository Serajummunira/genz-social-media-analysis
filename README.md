📱 # Gen-Z Social Media Usage and Mental Health Analysis.

A data science investigation into social media usage patterns and mental health
outcomes among Generation Z (ages 18–26).

## Project Overview
This project analyzes social media usage patterns among Generation Z users and examines the relationship between daily usage behavior and mental health scores.

The analysis was conducted using a real-world Kaggle dataset containing approximately 1 million records. A random sample of 10,000 records was selected for analysis to make the project computationally efficient while maintaining representativeness.

## Research Objective
The main objective of this project is to understand whether social media usage patterns are associated with mental health outcomes among Gen-Z users.

## Research Questions
1. What are the most popular social media platforms among Gen-Z users?
2. How much time do Gen-Z users spend on social media daily?
3. Is there a relationship between daily usage hours and mental health score?
4. Does night-time social media usage influence usage patterns and mental health outcomes?
5. Do usage patterns vary by gender or country?

## Dataset
- Source: Kaggle Gen-Z Social Media Usage Dataset
- Original size: Approximately 1,000,000 records
- Sample used: 10,000 randomly selected records
- Variables: Age, gender, country, daily usage hours, primary platform, number of platforms used, purpose, average session minutes, night usage, mental health score, addiction level, and screen time before sleep.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Methods
The project uses Exploratory Data Analysis (EDA), including:

- Data cleaning
- Random sampling
- Descriptive statistics
- Frequency analysis
- Bar charts
- Histograms
- Boxplots
- Scatter plots
- Correlation analysis

## Key Findings
- The average daily social media usage was approximately 3.5 hours.
- About 59% of users engaged in night-time social media usage.
- Instagram was the most popular platform in the sampled dataset.
- Platform choice had minimal impact on total daily usage.
- The strongest finding was a negative correlation between daily usage hours and mental health score.
- The correlation between daily usage hours and mental health score was approximately **r = -0.76**, suggesting that higher usage is associated with lower mental health scores.

## Main Insight
The analysis suggests that usage duration is more strongly associated with mental health outcomes than platform choice or number of platforms used.

## Visualizations Included
This project includes visualizations such as:

- Most popular social media platforms
- Distribution of daily usage hours
- Average usage by platform
- Purpose of social media usage
- Gender distribution
- Usage by gender
- Usage by country
- Daily usage vs. mental health score
- Night usage vs. daily usage
- Night usage vs. mental health score
- Number of platforms used vs. daily usage
- Correlation matrix

How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Upload the dataset file.
Run all cells in order.
The notebook will generate:
Cleaned dataset
Summary statistics
Visualizations
Correlation analysis
Ethical Considerations

The dataset used does not include personally identifiable information. The findings are interpreted as associations, not causal relationships. Mental health is complex and may be influenced by many factors beyond social media usage.

Limitations
The analysis is observational, so causation cannot be concluded.
The dataset may include self-reported or simulated values.
External factors such as lifestyle, sleep quality, and socioeconomic status were not included.
The analysis used a 10,000-record sample from the full dataset.

Author
Serajum Munira
Master’s Student in Information Quality
University of Arkansas at Little Rock
