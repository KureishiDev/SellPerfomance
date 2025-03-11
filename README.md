# Sales Analysis and Prediction

This repository contains a Python script for analyzing and predicting sales data. The main objective is to explore, visualize, and apply a linear regression model to predict sales values based on variables such as quantity and unit price. The script also includes steps for exploratory data analysis (EDA) and graphical visualizations.

## Project Structure

The script performs the following tasks:

### 1. Data Collection and Cleaning
- Loads sales data from a CSV file (replace `'dados_vendas.csv'` with the actual file path).
   
### 2. Exploratory Data Analysis (EDA)
- Displays descriptive statistics of the data.
- Visualizes the distribution of sales values.
- Plots total sales by region.
- Shows sales over time.

### 3. Data Visualization
- Scatter plot to visualize the relationship between the quantity of items sold and the sales value.
- Boxplot to compare sales by product category.

### 4. Predictive Modeling
- Prepares data by selecting relevant features for a linear regression model.
- Splits the data into training and test sets.
- Trains a linear regression model to predict sales values based on selected features.
- Evaluates the model's performance using Mean Squared Error (MSE).

## Requirements

To run this script, you will need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install them using pip:

pip install pandas matplotlib seaborn scikit-learn

## Usage
python sales_analysis.py
1. Place your sales data CSV file in the project directory or update the file path in the script.
2. Run the script to perform data analysis and prediction.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
