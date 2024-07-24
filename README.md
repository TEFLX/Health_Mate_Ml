# Health_Mate_ML_Model
This project analyzes WHO Global Health Observatory data using Python. It explores and preprocesses the dataset, then builds and evaluates machine learning models to predict health outcomes. The work demonstrates data analysis techniques and the application of AI to global health challenges.

# WHO Global Health Observatory Data Analysis and Prediction

This project analyzes data from the World Health Organization's Global Health Observatory (WHO GHO) and builds a predictive model using machine learning techniques.

## Project Structure

- `data_exploration.py`: Explores and visualizes the WHO GHO dataset.
- `data_preprocessing.py`: Preprocesses the data for machine learning.
- `model_training.py`: Trains and selects the best machine learning model.
- `model_evaluation.py`: Evaluates the trained model's performance.

## Dataset

The dataset used is the WHO GHO dataset (`WHO.csv`), available at [WHO GHO Data Repository](https://www.who.int/data/gho).

## Features

- Data loading and exploratory data analysis
- Data preprocessing and feature engineering
- Model training using multiple algorithms (Logistic Regression, Random Forest, SVM)
- Model evaluation and visualization of results

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

  
## Usage
 git clone https://github.com/your-username/who-gho-analysis.git
 cd who-gho-analysis


## Code Structure

**data_exploration.py:** 

Loads and explores the dataset
Generates distribution plots and correlation heatmaps


**data_preprocessing.py:**

Handles missing values
Encodes categorical variables
Normalizes numerical features
Splits data into training and testing sets


**model_training.py:**

Trains multiple models (Logistic Regression, Random Forest, SVM)
Selects the best performing model
Saves the best model


**model_evaluation.py:**

Loads the best model
Evaluates model performance
Generates confusion matrix and classification report



## Results
**The scripts generate:**

Exploratory data analysis visualizations
Preprocessed datasets
Trained machine learning model
Model performance metrics and visualizations

## Future Work

Implement more advanced feature engineering techniques
Explore ensemble methods and neural networks
Develop a web application for predictions
Perform time series analysis on temporal WHO data

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.
## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
## Acknowledgments

World Health Organization for providing the Global Health Observatory data
Contributors to pandas, scikit-learn, matplotlib, and seaborn libraries






```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib


