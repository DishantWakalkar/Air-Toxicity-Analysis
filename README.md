# Air Toxicity Prediction

This is my Third Year project which aims to predict air toxicity levels in Mumbai, India, focusing on pollutant concentrations at three locations: Chakala, Kurla, and the Airport. The goal is to find the best algorithm for pollutant data using machine learning models like Linear Regression, Random Forest, Decision Tree, LSTM, and XGBoost. Predictions from each model are compared using RMSE.

## Project Structure
In `Version 1.0` folder all demo files are present. On which we performed trial and error.
In `Version 2.0` folder all the final files are present. On which we performed final analysis.
The project is organized into two main folders: `data` and `notebook` which is inside `Version 2.0`.

### Data

The `data` folder contains two subfolders: `raw` and `processed`.

- `raw`: Contains the raw pollutant concentration data for the three locations in Mumbai.
- `processed`: Contains the preprocessed data, ready for analysis and modeling.

### Notebook

The `notebook` folder contains Python notebooks organized into four subfolders: `EDA`, `Prediction`, `Forecast`, and a temporary/dump folder.

- `EDA`: Contains notebooks for exploratory data analysis.
- `Prediction`: Contains notebooks for building and evaluating prediction models using various machine learning algorithms.
- `Forecast`: Contains notebooks for forecasting pollutant concentrations.
- `temp/dump`: A temporary folder for storing miscellaneous files and work-in-progress notebooks.

## References


- [sciencedirect.com](https://www.sciencedirect.com/science/article/abs/pii/S0959652622042287): Modeling air quality prediction using a deep learning approach: Method optimization and evaluation.
- [journalofbigdata.springeropen.com](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00548-1): Air-pollution prediction in smart city, deep learning approach.

## Additional Data Sources

- [Central Control Room for Air Quality Management](https://airquality.cpcb.gov.in/).
- [National Air Quality Index](https://airquality.cpcb.gov.in/AQI_India/)

## Getting Started

1. Clone the repository to your local machine.
2. Install the required Python packages.
3. Run the notebooks in the following order: Preprocessing, EDA, Prediction, and Forecast.

## Contributing

Contributions to the project are welcome! If you'd like to contribute, please follow the standard GitHub workflow of forking the repository and creating a pull request.