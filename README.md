# Kaggle Projects Repository

Welcome to my Kaggle Projects repository! This repository contains my data science and machine learning projects, starting with an analysis of bike-sharing data in London. Each project includes detailed notebooks, datasets, and explanations of the methodologies used.

## Project: London Bike Sharing Analysis (credits: https://www.youtube.com/watch?v=nl9eZl1IOKI&t=511s)

### Overview
This project analyzes bike-sharing data in London, focusing on factors such as weather, time, and seasonality that influence bike rental counts. The dataset includes information such as temperature, humidity, wind speed, weather conditions, and whether the day is a holiday or weekend.

### Dataset
The dataset used in this project is `london_merged.csv`, which contains the following columns:
- **time**: Timestamp of the record.
- **count**: Number of bike rentals.
- **temp_real_C**: Real temperature in Celsius.
- **temp_feels_like_C**: "Feels like" temperature in Celsius.
- **humidity_percent**: Humidity percentage.
- **wind_speed_kph**: Wind speed in kilometers per hour.
- **weather**: Weather conditions (e.g., Clear, Rain, Snowfall).
- **is_holiday**: Whether the day is a holiday (1) or not (0).
- **is_weekend**: Whether the day is a weekend (1) or not (0).
- **season**: Season of the year (Spring, Summer, Autumn, Winter).

### Notebook: `london_merged.ipynb`
The Jupyter Notebook (`london_merged.ipynb`) contains the following steps:
1. **Data Loading**: The dataset is loaded using `pandas`.
2. **Data Exploration**: Basic exploration of the dataset, including column information, shape, and value counts for categorical variables.
3. **Data Cleaning**: Renaming columns for better readability and converting humidity values to percentages.
4. **Data Transformation**: Mapping numerical codes for weather and season to their corresponding categorical labels.
5. **Data Export**: The cleaned and transformed dataset is exported to an Excel file (`london_bikes_final.xlsx`).

### Key Findings
- The dataset contains **17,414 records** with **10 columns**.
- Weather conditions are categorized into **6 types**, with "Clear" being the most common.
- Seasons are evenly distributed across the dataset, with each season having approximately the same number of records.

### How to Use
1. **Clone the repository**:
   ```bash
   git clone https://github.com/solmuz/kaggleProjects.git
   # Navigate to the project directory:
   cd kaggleProjects
   # Open the Jupyter Notebook:
   jupyter notebook london_merged.ipynb
   # Install dependencies (if needed):
   pip install pandas numpy matplotlib seaborn


Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

Fork the repository.

Create a new branch (git checkout -b feature/YourFeatureName).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeatureName).

Open a pull request.
