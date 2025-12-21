# Sandor_Varsanyi_CAPB352_BDA_Project_2025
This repository is made for my final university project on the **IT for Business Data Analytics course in 2025**. It consists of a **_documented Python code_**, and the **_supporting documentation_**, which explains the **_repository's structure_** and the description about how to **_reproduce the reuslts_** and what were the **_key dependecies_**. 

## Project Overview 
* This project aims to **predict professional football players’ market values** using a comprehensive, multi-source dataset covering the **top five European leagues** (Premier League, La Liga, Serie A, Bundesliga, Ligue 1) for the **2020–2025 seasons**.

* The analysis integrates **player-level and team-level performance metrics** with historical market values to develop and compare multiple machine learning models. Beyond prediction accuracy, the project emphasizes **model interpretability** and **economic reasoning** behind player valuation.

*The work is submitted as the **final project** for the CAPB352 *Business Data Analytics* course.

## Research objectives 
- Build a **unified analytical dataset** from multiple football data sources  
- Explore **key performance drivers** of player market value  
- Compare **linear, tree-based, and neural network models**  
- Evaluate predictive performance using appropriate regression metrics  
- Apply **SHAP-based explainability** to interpret individual predictions  
- Assess limitations of purely performance-based valuation models  

# Repository Structure: 

This is my repository structure: 
├── Sandor_Varsanyi_CAPB352_final_project.ipynb   # Main analysis notebook
├── football_dataset_csv/                         # Raw and processed datasets
│   ├── player_stats/
│   ├── team_stats/
│   ├── market_value/
│   └── master_tables/
├── README.md                                     # Project documentation


# How to run the notebook?

All datasets are loaded dynamically from public GitHub raw URLs.
An active internet connection is required to run the notebook.

Important:
- Only full, valid GitHub raw URLs are used
- Truncated links containing "..." are not supported
- No local files are required for execution

To ensure reproducibility, the notebook should be run sequentially from top to bottom
using **Kernel → Restart & Run All**.
