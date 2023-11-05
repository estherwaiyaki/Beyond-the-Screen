# Beyond-the-Screen
Beyond the Screen: Movie Industry Analysis
Overview
Beyond the Screen is an in-depth analysis project that explores the intricate dynamics of the movie industry. By investigating various critical aspects such as production budgets, release strategies, and timing considerations, this project aims to provide valuable insights to production companies and stakeholders. The analysis delves into understanding the factors that significantly influence a movie's financial success, encompassing both domestic and international markets.

Business Problems Explored
Impact of Production Budget on Financial Performance: Investigates the influence of production budget on a film's financial success, aiming to understand if a higher budget directly correlates with increased profitability.
Impact of Production Budget on Gross Revenue: Explores how the production budget affects a movie's domestic and worldwide gross, analyzing the correlation between budget and revenue.
Impact of Release Month on Profitability: Investigates whether the month of release significantly impacts a movie's profitability, identifying the most favorable months for maximizing profits.
Impact of Release Day of the Week on Profitability: Explores whether the day of the week on which a movie is released influences its profitability, helping stakeholders optimize release strategies.

Data Understanding
The analysis uses the tn.movie_budgets dataset, including details about movies, production budgets, release dates, domestic gross, and worldwide gross. The initial exploration involved data cleaning, converting data types, and handling zero values to ensure data accuracy.

Data Preparation
Data cleaning involved dropping rows with zero values in domestic and worldwide gross, ensuring a clean dataset for analysis. Feature engineering included creating columns for foreign gross, release months, release days of the week, and various profitability metrics.

Analysis and Visualization
Explored correlations between production budgets and domestic, foreign, and worldwide gross, indicating a positive correlation.
Identified the most profitable months for movie releases, tailoring insights for local, foreign, and global markets.
Analyzed the impact of the release day of the week on profitability, guiding strategic release planning.

Conclusion and Findings
The analysis challenged the common assumption that higher production budgets directly lead to increased profitability. 
It provided evidence-based recommendations for optimal release timing, guiding production companies on strategic decisions to maximize profits in various markets.

Repository Structure
Data: Contains the raw dataset (tn.movie_budgets.csv) used for analysis.
Notebooks: Includes Jupyter Notebooks detailing the entire analysis process.
Visualizations: Contains visual representations generated during the analysis.
README.md: Provides an overview of the project, business problems explored, data understanding, analysis, conclusions, and repository structure.
How to Use
