# NFL Skill Position Efficiency: Separating Production from Opportunity

## Project Overview

Traditional NFL leaderboards emphasize total production: rushing yards, receiving yards, touchdowns, receptions, and other counting statistics. Those measures are useful, but they can blur the difference between production driven by heavy workload and production created efficiently from available opportunities.

This project analyzes running back and wide receiver performance during the **2025 NFL regular season** to examine that distinction.

The central analytical question is:

> **Which NFL running backs and wide receivers created the most value in 2025 when both production and opportunity are considered?**

The project begins with exploratory data analysis and visualization using Python. A later phase will extend the analysis into machine learning.

## Project Status

**In Progress**

Current phase: Data acquisition, exploration, and preparation.

## Objectives

This analysis will:

- Examine 2025 NFL running back and wide receiver production.
- Compare raw production with workload and opportunity.
- Develop player efficiency metrics.
- Identify differences between high-volume and high-efficiency players.
- Investigate players whose production appears unusually high or low relative to workload.
- Compare performance patterns between running backs and wide receivers.
- Create clear visualizations communicating the major findings.
- Establish a clean analytical dataset that can support a future machine-learning extension.

## Analytical Questions

### 1. Who were the most productive skill-position players in 2025?

The first stage will examine traditional production metrics.

**Running backs**
- Rushing attempts
- Rushing yards
- Rushing touchdowns
- Receptions
- Receiving yards
- Total yards from scrimmage
- Total touchdowns

**Wide receivers**
- Targets
- Receptions
- Receiving yards
- Receiving touchdowns

### 2. Does greater opportunity necessarily result in better performance?

Workload will be compared with production using relationships such as:

- Carries vs. rushing yards
- Targets vs. receiving yards
- Touches vs. yards from scrimmage

The analysis will investigate whether the highest-volume players are also the most efficient.

### 3. Which players were the most efficient?

Potential efficiency measures include:

**Running backs**
- Yards per carry
- Yards per touch
- Rushing yards per game
- Touches per game
- Touchdown rate

**Wide receivers**
- Catch percentage
- Yards per reception
- Yards per target
- Receiving yards per game
- Touchdown rate

The final metrics will be selected during the analysis based on their usefulness and the available data.

### 4. Can players be classified by workload and efficiency?

Players will be grouped into performance profiles based on opportunity and efficiency.

Potential categories include:

- High workload / high efficiency
- High workload / low efficiency
- Low workload / high efficiency
- Low workload / low efficiency

The analysis will determine appropriate thresholds using statistical measures such as means, medians, or percentiles.

### 5. Who were the most notable outliers?

The analysis will identify players whose performance stands out relative to workload, including:

- High-volume, high-efficiency players
- High-volume, lower-efficiency players
- Lower-volume, high-efficiency players

The goal is to identify patterns from the data before incorporating outside football narratives.

### 6. How did running back and wide receiver production differ?

Position-level analysis will compare:

- Average workload
- Median workload
- Average efficiency
- Median efficiency
- Production variability
- Touchdown rates
- Distribution of player performance

## Data Scope

The project will use publicly available NFL data for the **2025 regular season**.

The initial player population will include:

- Running backs
- Wide receivers
- 2025 regular-season performance only

A minimum-opportunity threshold will be developed during exploratory analysis to prevent very small samples from distorting efficiency rankings.

## Tools

### Python
Primary analytical language.

### pandas
Used for data inspection, filtering, cleaning, grouping, aggregation, sorting, feature creation, and missing-value analysis.

### NumPy
Used for numerical calculations, conditional classification, statistical thresholds, percentile-based analysis, and feature creation.

### Matplotlib
Used to create player leaderboards, bar charts, scatter plots, opportunity-vs-production visualizations, efficiency comparisons, and player workload-efficiency profiles.

### Jupyter Notebook
Primary analytical environment.

## Project Milestones

### Phase 1 — Data Exploration and Preparation
- Load 2025 NFL player data.
- Inspect dataset dimensions and structure.
- Review available variables.
- Check missing values.
- Identify duplicates.
- Filter the dataset to relevant positions.
- Confirm regular-season records.
- Determine an appropriate minimum-opportunity threshold.

### Phase 2 — Production Analysis
- Examine traditional player production.
- Create player leaderboards.
- Develop additional calculated variables.
- Compare RB and WR production.

### Phase 3 — Efficiency Analysis
- Develop relevant player efficiency metrics.
- Compare volume and efficiency.
- Investigate relationships between opportunity and production.
- Identify noteworthy players and outliers.

### Phase 4 — Player Profiles
- Develop workload and efficiency thresholds.
- Classify players into performance groups.
- Compare player archetypes.
- Identify potentially underutilized efficient performers.

### Phase 5 — Visualization and Storytelling
Planned visualizations include:

1. Production leaderboard
2. Opportunity vs. production scatter plot
3. Efficiency leaderboard
4. Workload-efficiency player map

### Phase 6 — Final Analysis
- Summarize major findings.
- Document analytical limitations.
- Refine visualizations.
- Clean the notebook.
- Complete portfolio documentation.

## Planned Repository Structure

```text
nfl-2025-skill-position-efficiency/
├── README.md
├── notebooks/
│   └── nfl_player_efficiency_analysis.ipynb
├── data/
│   └── processed_player_data.csv
└── visuals/
    ├── production_leaders.png
    ├── opportunity_vs_production.png
    ├── efficiency_leaders.png
    └── player_archetypes.png
```

Files will be added as the analysis progresses.

## Skills Demonstrated

This project is designed to demonstrate practical use of:

- Exploratory data analysis
- Data cleaning
- Data validation
- pandas DataFrames
- Boolean filtering
- `groupby()`
- `agg()`
- `sort_values()`
- Feature engineering
- NumPy calculations
- Descriptive statistics
- Percentiles
- Outlier analysis
- Matplotlib visualization
- Analytical storytelling
- Sports analytics

## Future Machine Learning Extension

After the exploratory analysis is complete, this project will be expanded to investigate whether player opportunity and efficiency metrics can help predict future production.

Potential future topics include:

- Feature selection
- Train/test splitting
- Regression
- Model evaluation
- Predicted vs. actual production
- Comparing baseline and machine-learning models

Machine learning is intentionally excluded from the initial phase so the exploratory analysis and data preparation can be developed independently first.

## Author

**Kiran Williams**

M.S. Data Analytics Candidate | MBA Candidate

[GitHub Portfolio](https://github.com/keyswill/data-analytics-portfolio)
