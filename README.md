# Analysis of PMGSY Scheme

This repository contains an analysis of the Pradhan Mantri Gram Sadak Yojana (PMGSY) scheme using a dataset of road works and expenditures across various states in India.

## Table of Contents
- [Introduction](#introduction)
- [Setup](#setup)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
The PMGSY scheme aims to provide all-weather road connectivity to unconnected habitations in rural areas. This analysis explores the sanctioned and completed road works, expenditure per kilometer, and other relevant metrics across different states.

## Setup
To run the analysis, ensure you have the following dependencies installed:

\`\`\`bash
pip install pandas numpy matplotlib
\`\`\`

## Data
The dataset consists of the following columns:
- \`STATE_NAME\`
- \`DISTRICT_NAME\`
- \`PMGSY_SCHEME\`
- \`NO_OF_ROAD_WORK_SANCTIONED\`
- \`NO_OF_ROAD_WORKS_COMPLETED\`
- \`NO_OF_ROAD_WORKS_BALANCE\`
- \`LENGTH_OF_ROAD_WORK_SANCTIONED_KM\`
- \`COST_OF_WORKS_SANCTIONED_LAKHS\`
- \`LENGTH_OF_ROAD_WORK_COMPLETED_KM\`
- \`EXPENDITURE_OCCURED_LAKHS\`
- \`LENGTH_OF_ROAD_WORK_BALANCE_KM\`

## Analysis
1. **Data Cleaning**: Dropped columns related to bridges as they are not part of this analysis.
2. **Expenditure Calculations**:
   - Calculated the expenditure per kilometer sanctioned and actual expenditure per kilometer.
   - Filtered out rows with zero values in key columns.
3. **Frequency Distribution**: Analyzed the frequency distribution of road works across different states.
4. **State and Scheme Summary**: Grouped data by state and scheme, and plotted the total road lengths completed.
5. **Expenditure Distribution**: Visualized the expenditure distribution using pie charts for different schemes and states.
6. **Balance Road Length**: Summarized and plotted the balance road length by state.

## Results
- The analysis covers a total of 2245 constructions across the country.
- The top three states with the most constructions are Uttar Pradesh, Madhya Pradesh, and Rajasthan.
- Detailed visualizations and summaries are provided in the notebook.

## Conclusion
This analysis provides insights into the progress and expenditure of the PMGSY scheme. The visualizations highlight the distribution of road works and expenditures across different states and schemes.
EOL
