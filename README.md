# IPL_DATA_Exploration_Project

#IPL Auction 2023 Analysis
This repository contains a data analysis project focusing on the IPL (Indian Premier League) Auction 2023 dataset. The project aims to extract insights from the auction data, including player statuses (retained, sold, unsold), their nationalities, player styles, and their base and final prices.

Project Description
The project performs the following key steps:

Data Loading: Reads the iplauction2023.csv file into a Pandas DataFrame.

Initial Data Inspection: Displays the first few rows and checks for data types and non-null values.

Status Distribution Analysis: Analyzes the distribution of player statuses (RETAINED, SOLD, UNSOLD).

Data Consistency Checks: Validates and potentially corrects inconsistencies related to base price (in lacs), final price (in lacs), and franchise columns based on the player's status.

Data Source
The data used in this analysis is from the iplauction2023.csv file, which is assumed to be present in the project directory

#Analysis Highlights
The analysis provides initial insights into:

The overall structure of the IPL 2023 auction data.

The number of players who were retained, sold, or went unsold.

Identification of potential data entry errors or inconsistencies related to pricing and franchise information based on player status.

Further analysis could include:

Detailed statistical analysis of sold players (average price by style, nationality, etc.).

Visualization of auction trends.

Predictive modeling for player prices or auction outcomes.

Contributing
Contributions are welcome! If you have suggestions for improvements, new analyses, or bug fixes, please open an issue or submit a pull request.

License
This project is open-source and available under the MIT License
