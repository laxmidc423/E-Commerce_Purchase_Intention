# E-Commerce_Purchase_Intention

This repository contains the project files for an E-Commerce Purchase Intention Model. The goal of this project is to predict whether a user will make a purchase based on their browsing behavior and other relevant data.

## Project Files

- **ecommerce purchase intention.pdf**: Detailed report of the project, including data analysis, methodology, results, and conclusions.
- **ecommerce purchase intention.html**: An HTML version of the project report.
- **online_shoppers_intention.csv**: The dataset used for this project, containing features related to online shoppers' behavior.
- **file___code_updated.py**: The Python script containing the code used to build and evaluate the predictive model.

## Dataset

The dataset `online_shoppers_intention.csv` contains the following features:

- `Administrative`, `Administrative_Duration`: Number of pages and total time spent in the administrative category.
- `Informational`, `Informational_Duration`: Number of pages and total time spent in the informational category.
- `ProductRelated`, `ProductRelated_Duration`: Number of pages and total time spent in the product-related category.
- `BounceRates`, `ExitRates`, `PageValues`, `SpecialDay`: Metrics related to user behavior on the website.
- `Month`, `OperatingSystems`, `Browser`, `Region`, `TrafficType`: Categorical features representing various user attributes.
- `VisitorType`, `Weekend`: Indicators of user type and whether the visit was on a weekend.
- `Revenue`: The target variable indicating whether the user made a purchase.

## Code Overview

The Python script `file___code_updated.py` includes the following steps:

1. **Data Loading and Preprocessing**:
    - Loading the dataset
    - Handling missing values
    - Encoding categorical features
    - Scaling numerical features

2. **Model Building**:
    - Splitting the dataset into training and testing sets
    - Training various machine learning models (e.g., Logistic Regression, Decision Trees, Random Forest)
    - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score

3. **Model Evaluation and Selection**:
    - Comparing model performance
    - Selecting the best-performing model for final prediction

## How to Use

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/your-username/ecommerce-purchase-intention.git
    ```

2. Navigate to the project directory:
    ```sh
    cd ecommerce-purchase-intention
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the Python script to execute the model:
    ```sh
    python file___code_updated.py
    ```

## Results

The results of the analysis and model performance are documented in the `ecommerce purchase intention.pdf` and `ecommerce purchase intention.html` files.

## Conclusion

This project demonstrates how machine learning can be applied to predict e-commerce purchase intentions based on user behavior data. The selected model provides valuable insights that can help in optimizing marketing strategies and improving user experience on e-commerce platforms.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the providers of the dataset and all the contributors who made this project possible.

---

Feel free to modify this README file to better suit the specifics of your project.
