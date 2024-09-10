
# Telecom Churn Prediction Project

## Project Overview

This project aims to predict customer churn for a telecommunications provider using machine learning techniques. The primary goal is to identify which customers are at risk of churning (leaving the service) and understand the factors driving churn. By leveraging customer data, the model helps the company take proactive actions to retain customers, optimize marketing strategies, and improve overall service offerings.

Key takeaways from this analysis include:
- Strong correlation between customer service interactions and churn.
- Younger customers (aged 25-40) are at a higher risk of churning.
- Voice mail plans are becoming less relevant for churn prediction.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/telecom-churn-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd telecom-churn-prediction
   ```

3. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate # On Windows use `env\Scripts\activate`
   ```

4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Launch Jupyter Notebook to explore the analysis:
   ```bash
   jupyter notebook
   ```

## Usage

### Data Preparation
- The dataset used for this project is sourced from Kaggle's **Customer Churn Prediction 2020** dataset. Ensure that the dataset is placed in the `data/` folder.
- Data preprocessing steps include handling missing values, feature engineering, and splitting the dataset into training and test sets.

### Model Training and Evaluation
- The project leverages machine learning models such as **Random Forest** and **Logistic Regression** to predict churn.
- After training the models, metrics like accuracy, precision, recall, and F1-score are calculated to evaluate performance.

### Running the Notebook
- Open the `notebook.ipynb` file in Jupyter and run each cell to see the data exploration, model training, and evaluation.

### Example Output
After running the model, you'll see results like:

- **Churn Prediction Accuracy**: 85%
- **Confusion Matrix**: Demonstrates the true positive and false positive rates for churn prediction.
  
Here are key insights:
1. Customers who make more than three calls to customer service are significantly more likely to churn.
2. Younger customers (aged 25-40) with high usage of day minutes are at a higher risk of leaving.
3. Voice mail plans no longer seem to impact customer churn rates significantly.

## Results and Conclusion

1. **Customer Service Impact**: High customer service interaction is a strong indicator of churn. Improving customer support quality is essential for retention.
2. **Target Younger Customers**: Younger customers require more personalized plans to mitigate dissatisfaction.
3. **Re-evaluate Voice Mail Plans**: Voice mail services are becoming less relevant and may not need to be emphasized in customer retention strategies.

By focusing on these key areas, telecom companies can reduce churn, enhance customer satisfaction, and maintain a competitive edge.


