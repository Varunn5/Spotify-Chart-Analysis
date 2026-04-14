# Spotify Chart Analysis: Longevity & Ranking Dynamics

## Overview
This project analyzes Spotify chart data (2017–2022) to understand how songs and artists perform over time. The focus is on identifying patterns in chart longevity, ranking dynamics, and the concentration of success across artists.

## Key Questions
- How does peak chart rank relate to how long a song stays on the charts?
- How concentrated is chart success across artists?
- Do a small number of artists dominate overall chart presence?

## Approach
- Processed 2,191 daily Spotify chart files (~438K rows)
- Cleaned and standardized data using Python (pandas)
- Created track-level metrics including:
  - Days on chart
  - Peak rank
  - Average rank
  - Run length
- Aggregated artist-level performance and distribution

## Key Insights
- Strong negative correlation (-0.405) between peak rank and longevity, meaning higher-ranking songs tend to stay on charts longer
- The top 10% of artists account for ~66% of total chart days, indicating heavy concentration of success
- High inequality in chart presence (Gini coefficient: 0.802), suggesting a small number of artists dominate listener attention

## Why This Matters
These findings highlight how music consumption is concentrated among top artists and tracks. This has implications for:
- Recommendation systems and discovery algorithms
- Artist growth tools and exposure strategies
- Platform-level decisions around surfacing new vs. established artists

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
