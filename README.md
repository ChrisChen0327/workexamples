# Project 1: GIS + Causal Inference in Education Policy at Chicago
## Overview
This repository contains the analytical project evaluating Illinois's Evidence-Based Funding (EBF) policy implemented in 2017, focusing on its impact on student academic performance and school district financial health. Conducted by Rui (Chris) Chen and Xinyue Zhou from the Harris School of Public Policy at the University of Chicago.

## Research Questions
1. **Impact of EBF Policy**: How has the implementation of the EBF policy affected student performance in English Language Arts (ELA) and Mathematics, as well as district financial health?
2. **Mediation by Financial Health**: Does district financial health mediate the relationship between EBF policy implementation and student performance?

## Project Structure
- **Data**: Contains datasets including EBF allocations, student performance metrics, financial scores, and socioeconomic indicators.
- **Scripts**: R scripts for data cleaning, merging, regression analysis, and spatial analysis.
- **Spatial Analysis**: GIS mapping and spatial autocorrelation analysis results.

## Data Sources
- **Illinois Board of Education**: EBF funding and district-level financial data (2015-2019).
- **Illinois Report Card (PARCC)**: Student proficiency rates in ELA and Math.
- **National Center for Education Statistics (NCES)**: Socioeconomic and financial expenditure data.
- **School District Financial Profiles**: Financial health indicators (liquidity, debt management, expenditure-to-revenue ratios).

## Methodology
### Statistical Analysis
- Conducted in R:
  - **Fixed effects regression analysis** assessing the direct effects of EBF policy.
  - **Mediation analysis** exploring how financial health scores mediate policy effects.

### Spatial Analysis
- **QGIS**: Visual mapping of performance and financial conditions.
- **GeoDa**: Spatial autocorrelation and Local Indicators of Spatial Association (LISA) analysis.

## Key Findings
- Statistically significant improvements in student proficiency in ELA and Math post-EBF implementation.
- Moderate positive effect on district financial health scores post-policy.
- Financial health partially mediates the policy's impact on student performance, though the mediation effect is relatively small.
- Spatial analysis revealed mixed patterns, with some regions showing clearer relationships between increased funding and performance improvements.

## Limitations and Future Work
- Limited by short timeframe and lack of granular school-level spending data.
- Future analyses should focus on longer-term data and include granular financial details to better identify heterogeneous impacts across districts and schools.

## Authors
- **Rui (Chris) Chen**
- **Xinyue Zhou**  
*Harris School of Public Policy, University of Chicago*
