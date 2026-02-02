# Prague Airbnb Market Analysis

Analysis of ~9,400 Airbnb listings in Prague to answer: **What determines success in Prague's short-term rental market?**

## Key Finding

Prague's market has crossed a **professionalization threshold** — traditional quality signals (ratings, apartment condition) no longer differentiate winners. Success now depends on operational optimization and platform credentialing (Superhost, Instant Book).

## Methodology

1. **Data Source**: Inside Airbnb listings dataset (12-month period)
2. **Exploratory Analysis**: Distribution patterns, geographic segmentation, host profiling
3. **Comparative Analysis**: Top 20% vs bottom 40% performers
4. **Tools**: Python, pandas, Plotly for interactive visualizations

## Quick Start

```bash
# Setup environment
conda env create -f environment.yml
conda activate airbnb-insights

# Run notebooks
jupyter lab
```

Open notebooks in order:
- `01_prague_eda_quick.ipynb` — Exploratory data analysis
- `02_prague_airbnb_insights.ipynb` — Strategic insights

## Project Structure

```
├── data/raw/          # Source data (listings.csv)
├── notebooks/         # Analysis notebooks + HTML reports
└── environment.yml    # Dependencies
```

## Key Insights

| Insight | Detail |
|---------|--------|
| Market control | 77% supply from multi-listing hosts |
| Rating inflation | 85% have 4.5+ stars (broken signal) |
| Zombie listings | 23% with zero reviews in 12 months |
| Top performer edge | Superhost = 3x performance gap |
