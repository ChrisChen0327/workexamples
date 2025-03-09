# Project 1: HTML+ArcGIS: Mapping Out-of-School Programs and Violent Crime in Chicago

## Overview
This repository contains an interactive GIS mapping project analyzing the distribution of Out-of-School Time (OST) programs and violent crime incidents in Chicago's South and West communities, developed by Chris Chen at the Harris School of Public Policy, University of Chicago.

## Project Goals
- Visualize the distribution and availability of OST programs from 2020 to 2024.
- Explore potential spatial correlations between OST program density and community violence.
- Provide policymakers and stakeholders with actionable insights to support resource allocation and policy advocacy.

## Data Sources
- **OST Programs**: Sourced from [My CHI. My Future](https://explore.mychimyfuture.org/interactive-map), including over 170,000 programs.
- **Violent Crime Data**: Collected from the City of Chicago's public datasets.

## Project Structure
- **Data Cleaning and Preparation**: Performed in R, removing duplicates and filtering data to include 22 specific Chicago communities.
- **GIS Mapping**: Developed using ArcGIS for enhanced data visualization and user interaction.

## Features
- **Interactive Time Slider**: Adjusts map data over three-month intervals, illustrating temporal changes.
- **Violence Layer**: Optional map layer displaying violent crime incidents to allow users to investigate potential associations with OST program availability.
- **Interactive Elements**:
  - Program-specific popups displaying detailed information.
  - Search functionality to quickly locate programs by name, type, or location.
  - Community-level filters for focused analysis.

## Data Sources and Tools
- **My CHI, My Future Database**
- **City of Chicago Open Data Portal**
- **R** for data preprocessing
- **ArcGIS** for professional-grade mapping and visualization

## Design Choices and Rationale
- **Time Slider**: Facilitates examination of temporal changes and trends in OST program availability.
- **Violence Layer**: Optional toggle to juxtapose OST programs with violent crime data, enabling exploratory analyses of spatial relationships.
- **Interactive Popups and Filters**: Enhances user engagement and accessibility to detailed program data.

## Author
- **Chris Chen**, Harris School of Public Policy, University of Chicago



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

## Authors
- **Rui (Chris) Chen**
- **Xinyue Zhou**  
*Harris School of Public Policy, University of Chicago*
