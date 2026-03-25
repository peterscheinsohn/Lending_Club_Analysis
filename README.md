# Lending_Club_Analysis# 

## Overview
This project analyzes a large dataset from the Fintech field, focusing on borrower records from US users from 2007 to 2018. The dataset includes comprehensive information about borrowers, such as loan amounts, risk tiers, and default rates. Initial source file was too big (1.46 Gb) to be uploaded here. You can find original data source here:
https://www.kaggle.com/datasets/wordsforthewise/lending-club/data
## Technologies Used
- Python
- Pandas
- DuckDB
- Tableau
- GitHub

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/loan_club_analysis.git`
2. Navigate to the project directory: `cd loan_club_analysis`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the data cleaning script: `python src/data_cleaning.py`

## Usage
- Visualize the cleaned data using Tableau: `tableau src/visualization.py`
- Analyze risk tiers: `python src/risk_analysis.py`

## Key Insights
- **Big Data Analysis: It's entirely possible to work with and analyze large datasets meaningfully, though it requires special attention. Not all standard software can handle such large datasets in their native state.
- **Regional Concentration: There's a clear, non-homogeneous distribution of borrowers across US states, with a concentration in California, New York, Texas, and Florida.
- **Risk Classification: This model allows for clear risk classification based on initial data (DTI, loan purpose, credit utilization rate), though it doesn't predict default rates.
- **Data Pipeline: This project demonstrates how a scalable data pipeline can be built from a large real-world dataset, enabling structured risk analysis and serving as a reusable template for financial analysts working with similar loan data.
## Visuals
https://public.tableau.com/app/profile/peter.scheinsohn/viz/LoanClub_17553336299440/Dashboard1?publish=yes
## Disclaimer
This repository is for educational purposes only. The code provided is intended to illustrate the methodology and should not be used for commercial or competitive purposes without proper attribution.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
