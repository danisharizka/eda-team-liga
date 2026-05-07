# Football Player Performance Analysis

Comprehensive data analysis project exploring the relationship between player performance metrics and market value across top European football leagues.

## Project Overview

This project analyzes football player statistics from multiple leagues (La Liga, Premier League, Bundesliga, Serie A, Ligue 1, MLS, etc.) to uncover insights about player performance, market valuation, and league characteristics.

**Key Questions:**

- What factors influence player market value?
- How do performance metrics correlate with each other?
- Which leagues have the highest-performing players?
- What makes a player efficient?

## What You Can Do

### 1. **Interactive Dashboard**

Explore data dynamically with filters and visualizations. 

**Live Demo: [https://danisharizka.github.io/eda-team-liga/dashboard/](https://danisharizka.github.io/eda-team-liga/dashboard/)**

**Features:**

- Filter by league
- Select variables for analysis
- View correlations in real-time
- Interactive charts with hover details
- Responsive design

### 2. **Jupyter Notebooks**

Deep dive into the analysis with step-by-step notebooks.

**Workflow:**

```
Raw Data → Cleaning → Visualization → Statistical Analysis
```

**Notebooks:**

- `01_data_loading_and_cleaning.ipynb` - Data preparation
- `02_visualization.ipynb` - Visual exploration
- `03_statistical_analysis.ipynb` - Statistical tests & insights

## Dataset

### Source

- https://www.kaggle.com/datasets/mohamedhanyyy/top-football-leagues-scorers/data
- https://www.kaggle.com/datasets/kriegsmaschine/soccer-players-values-and-their-statistics

### Features (16 columns)

- **Identifiers:** Country, League, Club, Player Names, Year
- **Playing Time:** Matches_Played, Substitution, Mins
- **Performance:** Goals, xG, Shots, OnTarget
- **Metrics:** xG Per Avg Match, Shots Per Avg Match, On Target Per Avg Match
- **Valuation:** value (market value in USD)

### Statistics

- **159 players** across multiple leagues
- **Top leagues:** La Liga, Premier League, Bundesliga, Serie A, Ligue 1, MLS
- **Market values:** $2.5M - $120M+
- **Goal range:** 2 - 38 goals per season

## Visualizations

### Dashboard Charts

1. **Distribution Pie Chart** - Player distribution across leagues
2. **Scatter Plot** - Correlation analysis between any two variables
3. **Top 10 Bar Chart** - Highest market value players
4. **Box Plot** - Distribution and outlier detection
5. **Correlation Heatmap** - All numeric variable relationships
6. **Dynamic Analysis** - Real-time interpretation

### Notebook Visualizations

- Distribution plots (histogram + KDE)
- Q-Q plots for normality testing
- Box plots for outlier detection
- Grouped bar charts by league
- Time series analysis
- Multi-variable comparisons

## Technical Stack

### Dashboard

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Charts:** Plotly.js
- **Fonts:** Google Fonts (Syne, DM Sans)
- **Design:** Glass morphism, dark theme, responsive grid

### Analysis

- **Python 3.8+**
- **pandas** - Data manipulation
- **numpy** - Numerical computing
- **matplotlib** - Base plotting
- **seaborn** - Statistical visualizations
- **scipy** - Statistical tests

## Statistical Methods

### Descriptive Statistics

- Mean, median, mode, standard deviation
- Quartiles, IQR, range
- Skewness and kurtosis

### Inferential Statistics

- Shapiro-Wilk test (normality)
- Pearson correlation
- T-tests (comparing two groups)
- ANOVA (comparing multiple groups)

### Efficiency Metrics

- Goals per shot
- Shot accuracy (%)
- Goals per match
- xG vs actual goals difference

## Dashboard Features

### Interactive Controls

- **League Filter** - Focus on specific leagues
- **Variable Selection** - Choose X and Y axes dynamically
- **Reset Button** - Return to default view
- **Apply Filter** - Update all visualizations

### Real-time Analysis

- Correlation coefficients
- Statistical significance
- Group comparisons
- Top performers
- Outlier detection

### Responsive Design

- Works on desktop, tablet, mobile
- Adaptive chart layouts
- Touch-friendly controls
- Fast performance

## Use Cases

### For Analysts

- Identify undervalued players
- Compare league characteristics
- Validate performance metrics
- Discover correlations

### For Coaches

- Evaluate player efficiency
- Compare shooting performance
- Assess xG vs actual goals
- Track league trends

### For Fans

- Explore favorite players
- Compare leagues
- Understand market values
- Learn about statistics

### For Students

- Learn data analysis workflow
- Practice statistical methods
- Understand visualizations
- Build portfolio project

## License

This project is for educational purposes. Dataset sources should be properly attributed.

## Acknowledgments

- Data sources: [https://www.kaggle.com/datasets/mohamedhanyyy/top-football-leagues-scorers/data](https://www.kaggle.com/datasets/mohamedhanyyy/top-football-leagues-scorers/data), [https://www.kaggle.com/datasets/kriegsmaschine/soccer-players-values-and-their-statistics](https://www.kaggle.com/datasets/kriegsmaschine/soccer-players-values-and-their-statistics)
- Visualization: Plotly.js community
- Inspiration: Sports analytics community
