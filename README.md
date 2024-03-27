# Synthetic Time Series Data Analysis

This project involves the analysis of synthetic time series data generated for agricultural experiments. The data consists of various environmental factors such as temperature, rainfall, and soil pH, along with corresponding yield, biomass, and canopy measurements.

## Overview

The synthetic time series data was generated to simulate agricultural experiments with different treatment combinations. Each treatment combination was subjected to varying environmental conditions, and the corresponding yield, biomass, and canopy measurements were recorded over time.

## Data Description

The dataset contains the following columns:

- `Time`: Timestamp indicating the date of observation.
- `Treatment`: Categorical variable representing different treatment combinations.
- `Temperature`: Numeric variable indicating the temperature recorded during each observation.
- `Rain`: Numeric variable representing the amount of rainfall recorded during each observation.
- `Soil_pH`: Numeric variable indicating the soil pH measured during each observation.
- `Yield`: Numeric variable representing the yield recorded for each treatment combination.
- `Biomass`: Numeric variable indicating the biomass measured for each treatment combination.
- `Canopy`: Numeric variable representing the canopy coverage measured for each treatment combination.

## Analysis

The data analysis involves:

- Exploratory Data Analysis (EDA) to understand the distribution and relationships between variables.
- Principal Component Analysis (PCA) for dimensionality reduction and visualization.
- Multiple regression modeling to predict yield, biomass, and canopy based on environmental factors.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

## Usage

To use this project:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter Notebook (`TS_data1.ipynb`) to execute the data analysis pipeline.
4. Modify the code as needed for further analysis or customization.

## Contributors

- hello it's me (https://github.com/HindCatBlacknDark)

Feel free to contribute by opening issues, suggesting improvements, or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
