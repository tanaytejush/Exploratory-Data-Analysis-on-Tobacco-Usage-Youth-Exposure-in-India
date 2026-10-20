# EDA on Tobacco Usage and Youth Exposure in India

An in-depth exploratory analysis of **tobacco usage patterns, youth exposure to tobacco marketing, and policy enforcement gaps** across Indian states and union territories. It highlights public health risks and points to where targeted anti-tobacco action would help most.

## About the data

The data comes from nationwide health and education surveys. It covers current and lifetime tobacco use, age of initiation, exposure to marketing, and compliance with **COTPA** (the Cigarettes and Other Tobacco Products Act) in schools.

## Objectives

- Compare tobacco use across regions (cigarettes, bidi, smokeless tobacco)
- Assess how exposure to tobacco marketing relates to youth usage
- Find gaps in policy enforcement and school-level anti-tobacco measures
- Detect outlier regions that need focused intervention

## Key findings

1. **Regional patterns**: Bihar, Mizoram, Nagaland and Tripura show significantly higher usage than the national average. Rural areas report more tobacco use, especially smokeless tobacco and bidi.
2. **Youth exposure**: many students are still exposed to tobacco advertising despite legal restrictions, which points to COTPA enforcement lapses. Fewer than 40% of students in many regions noticed preventive messages.
3. **Age of initiation**: in some states children start as early as 12 to 13 years old.
4. **Policy enforcement**: 81% of schools know the tobacco-free guidelines, but only about 37% are authorised to collect fines.
5. **Outliers**: boxplot analysis identified states that are statistical outliers for current tobacco use, on both the high and low ends. These are candidates for targeted public health programmes.

## Methods

- Data cleaning and preprocessing
- Univariate and bivariate analysis
- Correlation heatmaps
- Outlier detection with boxplots
- Urban versus rural comparisons

## Files

| File | Description |
|------|-------------|
| `tobacco_eda.ipynb` | Analysis notebook |
| `datafile.csv` | Original survey data |
| `cleaned_tobacco_data.csv` | Cleaned dataset used in the notebook |

## Run it

```bash
pip install pandas numpy seaborn matplotlib jupyter
jupyter notebook tobacco_eda.ipynb
```

## Tech stack

Python (pandas, NumPy, seaborn, matplotlib), Jupyter Notebook


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
