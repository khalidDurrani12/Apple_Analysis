# Apple Analysis with PySpark

This project uses **PySpark** to analyze customer transaction data and identify purchasing patterns of Apple products, specifically focusing on iPhone and AirPods purchases.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Data](#data)
- [Setup Instructions](#setup-instructions)
- [Results](#results)
- [Contributors](#Contributors)
- [Portfolio](#Portfolio)

## Project Overview
The **Apple Analysis** project aims to:
1. Identify customers who purchased AirPods after buying an iPhone.
2. Identify customers who only purchased iPhones and AirPods.

By leveraging **PySpark**, we process large transactional datasets to extract meaningful insights on customer behavior.

## Technologies Used
- **PySpark**: For big data processing and analysis
- **Pandas**: For additional data manipulation
- **Python 3.x**: Main programming language

## Project Structure
The project consists of the following six files:

1. `apple_analysis.py`: The main script where the primary logic and analysis are performed.
2. `data_loading.py`: Handles the loading of transactional data.
3. `data_cleaning.py`: Ensures the dataset is cleaned (removing nulls, duplicates, etc.).
4. `data_transformation.py`: Applies the transformations needed to filter customers by product purchases.
5. `analysis_report.py`: Outputs the analysis results (e.g., lists of customers) to a CSV or console.
6. `requirements.txt`: Contains a list of dependencies for the project.

## Data
The dataset should include transaction records with fields like:
- `User ID`
- `Transaction Date`
- `Product Purchased`

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/khalidDurrani12/Apple_Analysis.git
   cd Apple_Analysis

## Project Structure
The project consists of the following files:

1. `apple_analysis.py`: The main script where the primary logic and analysis are performed.
2. `extractor.py`: Handles data extraction from the source (e.g., CSV).
3. `transform.py`: Performs data cleaning and transformations.
4. `loader.py`: Loads the transformed data into the target destination (e.g., CSV).
5. `loader_factory.py`: Provides a factory pattern for creating different types of loaders.
6. `reader_factory.py`: Provides different types of readers for data extraction.
## Results

The analysis provides key insights into purchasing behaviors related to Apple products, helping businesses tailor their marketing strategies.
"""

## Contributors

Khalid Khan - Data Analyst

## Portfolio

- <a href="https://khaliddurrani12.github.io/khalid0803.github.io/" target="_blank">Khalid Khan</a>

