



# Motor Vehicle Collisions - Crashes Dataset Analysis

## Overview

This project analyzes the "Motor Vehicle Collisions - Crashes" dataset, which contains information about motor vehicle collisions in New York City. The dataset includes various attributes such as crash date, time, location, contributing factors, and the types of vehicles involved.

## Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/sanjanchaudhari/motor-vehicle-collisions-crashes) and consists of 29 columns and over 1.9 million rows. The key columns include:

- **CRASH DATE**: Date of the crash.
- **CRASH TIME**: Time of the crash.
- **BOROUGH**: Borough where the crash occurred.
- **ZIP CODE**: ZIP code of the crash location.
- **LATITUDE** and **LONGITUDE**: Geographic coordinates of the crash location.
- **NUMBER OF PERSONS INJURED**: Number of people injured in the crash.
- **NUMBER OF PERSONS KILLED**: Number of fatalities in the crash.
- **CONTRIBUTING FACTOR VEHICLE 1**: Contributing factor for the first vehicle involved.
- **VEHICLE TYPE CODE 1**: Type of the first vehicle involved.

## Installation

To run the analysis on this dataset, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/motor-vehicle-collisions-analysis.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the dataset:
    - You can use the `opendatasets` Python package to download the dataset directly from Kaggle.
    - Make sure you have your Kaggle API credentials ready.

    ```python
    import opendatasets as od
    od.download('https://www.kaggle.com/datasets/sanjanchaudhari/motor-vehicle-collisions-crashes')
    ```

4. Load the data:
    ```python
    import pandas as pd
    df = pd.read_csv('./motor-vehicle-collisions-crashes/Motor_Vehicle_Collisions_-_Crashes.csv')
    ```

## Usage

The project includes a series of Jupyter notebooks that walk through the analysis process:

1. **Data Cleaning**: Handling missing values, converting data types, and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA)**: Identifying patterns, trends, and outliers in the data.
3. **Visualization**: Creating plots to visualize the distribution of crashes, locations, and contributing factors.
4. **Modeling (Optional)**: Building predictive models to understand the factors leading to collisions.

## Results

The analysis revealed the following key insights:

- The distribution of crashes varies significantly by borough, with the highest number in Manhattan.
- Most crashes occur during rush hours, suggesting a correlation with traffic congestion.
- Common contributing factors include driver inattention, failure to yield, and unsafe speed.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue.




