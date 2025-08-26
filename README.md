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
- **Regional Distribution**: The first interactive dashboard shows the regional distribution of borrowers across US states, factoring in loan purpose, loan duration (36/60 months), home ownership, and hardship flag.
- **Risk Tiers by Loan Approval**: The second image illustrates the distribution of the three risk tiers by loan approval stage, depending on the same factors.
- **Default Rate**: The third image reveals the total default rate, influenced by loan purpose, home ownership, loan duration, and more.

## Visuals
![Dashboard Screenshot](results/dashboard.png)

## Disclaimer
This repository is for educational purposes only. The code provided is intended to illustrate the methodology and should not be used for commercial or competitive purposes without proper attribution.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
