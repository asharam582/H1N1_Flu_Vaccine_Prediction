# H1N1 and Seasonal Flu Vaccination Prediction



## Background

Swine flu, caused by the H1N1 influenza virus, emerged as a pandemic in 2009, affecting millions worldwide. Vaccination plays a crucial role in preventing the spread of flu viruses. Understanding vaccination likelihood aids in effective public health strategies. This project aims to predict the probability of individuals getting vaccinated against H1N1 and seasonal flu based on demographic and behavioral factors.

## Challenge

The goal is to anticipate the likelihood of individuals getting vaccinated against H1N1 and seasonal flu. The dataset comprises responses from the 2009 National H1N1 Flu Survey (NHFS) by the CDC.

## Features

- **Demographic Data**: Age, education, race, sex, income, marital status, household details.
- **Behavioral Factors**: Awareness, concerns, preventive measures.
- **Healthcare Access**: Doctor recommendations, medical conditions, insurance coverage.
- **Geographical and Employment Details**: Geographic region, employment status, industry, occupation.

## Methodology

- **Data Preprocessing**: Handle missing values, encode categorical variables.
- **Model Training**: Employ machine learning algorithms like Random Forest, Gradient Boosting, and Logistic Regression.
- **Model Evaluation**: Assess model performance using metrics like ROC AUC score.
- **Feature Importance**: Determine the significance of features in predicting vaccination likelihood.

## Repository Structure

- `data/`: Contains datasets used for analysis.
- `notebooks/`: Jupyter notebooks for data preprocessing, modeling, and evaluation.
- `scripts/`: Python scripts for utility functions and data processing.
- `README.md`: Project overview, background, methodology, and instructions.
- `requirements.txt`: List of Python dependencies.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/h1n1-seasonal-flu-prediction.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Explore notebooks in `notebooks/` for data analysis and model building.

4. Execute scripts in `scripts/` for specific tasks like data preprocessing or model evaluation.

## Results

- Achieved ROC AUC scores:
  - H1N1 Vaccine Prediction: 0.83
  - Seasonal Vaccine Prediction: 0.86


## License

This project is licensed under the [MIT License](LICENSE).

