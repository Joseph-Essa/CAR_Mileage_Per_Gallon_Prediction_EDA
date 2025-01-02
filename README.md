# CAR Mileage Per Gallon Prediction (EDA)

## Project Overview
This project focuses on analyzing a car dataset to explore the factors influencing mileage per gallon (mpg). The goal is to understand key relationships between variables and their impact on car efficiency. The analysis provides insights that could help manufacturers and consumers prioritize features affecting fuel efficiency.

## Dataset
The dataset contains the following key features:
- **mpg**: Miles per gallon (target variable).
- **cylinders**: Number of cylinders in the car's engine.
- **displacement**: Engine displacement (in cubic inches).
- **horsepower**: Engine horsepower.
- **weight**: Weight of the car (in pounds).
- **acceleration**: Time to accelerate from 0 to 60 mph (in seconds).
- **model year**: Year of the car model.
- **origin**: Country of origin (1: USA, 2: Europe, 3: Asia).

The dataset is already cleaned and formatted for analysis.

## Exploratory Data Analysis
Several techniques were applied to uncover patterns and relationships in the data:
- **Descriptive Statistics**: Summarized the data using mean, median, standard deviation, and distribution checks.
- **Correlation Analysis**: Measured relationships between the target variable (mpg) and other features.
- **Visualizations**: Illustrated insights using various plots:
  - **Scatter Plots**: Explored relationships between numerical features and mpg.
  - **Histograms**: Analyzed distributions of features like weight and horsepower.
  - **Box Plots**: Identified outliers in variables such as displacement and acceleration.
  - **Bar Charts**: Compared mpg by categorical variables like origin.

## Key Insights
- Cars with fewer cylinders tend to have higher mpg.
- Engine horsepower and weight are inversely correlated with mpg.
- Cars from Japan generally exhibit better fuel efficiency compared to those from the USA and Europe.
- There is a clear trend of improving mpg over model years, likely reflecting advancements in technology.

## Conclusion
The analysis highlights the major contributors to fuel efficiency, such as weight and horsepower. It also underscores trends in car manufacturing that align with increasing consumer and regulatory demand for efficient vehicles.

## Usage
1. Clone this repository to your local machine.
2. Install the required dependencies (see Requirements section).
3. Open the Jupyter notebook `CAR_Mileage_Per_Gallon_Prediction_(EDA).ipynb` to explore the analysis.

## Requirements
The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

## How to Reproduce
To reproduce the analysis:
1. Ensure you have Python 3.7+ and Jupyter Notebook installed.
2. Install dependencies by running:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Run the notebook step by step to observe the data exploration and insights.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
