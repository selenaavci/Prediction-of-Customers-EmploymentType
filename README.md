### AutoInsurance Project

This project aims to predict the employment type of customers based on various features using a multiclass logistic regression model. The dataset used for this project is sourced from Kaggle and contains information such as customer details, policy information, and employment status.

#### Dataset Description
The dataset includes the following columns:
- Customer
- State
- Customer Lifetime Value
- Response
- Coverage
- Education
- Effective To Date
- EmploymentStatus
- Gender
- Income
- Location Code
- Marital Status
- Monthly Premium Auto
- Months Since Last Claim
- Months Since Policy Inception
- Number of Open Complaints
- Number of Policies
- Policy Type
- Policy
- Renew Offer Type
- Sales Channel
- Total Claim Amount
- Vehicle Class
- Vehicle Size

#### Logistic Regression Model
The logistic regression model is implemented using Python's scikit-learn library. It predicts the employment status of customers based on the provided features. The model is trained and evaluated using accuracy metrics.

#### Visualization
Visualization of the dataset is performed using seaborn and matplotlib libraries. Various plots such as histograms, count plots, box plots, and pair plots are generated to understand the distribution and relationships between different variables in the dataset.

### Code Files
- **autoinsurance_logistic_regression.py**: Contains the implementation of the logistic regression model for predicting employment status.
- **visualization_autoinsurance.py**: Includes code for visualizing the AutoInsurance dataset using seaborn and matplotlib.

### Usage
1. Clone the repository to your local machine.
2. Install the required dependencies mentioned in the `requirements.txt` file.
3. Run the `Multiclass Logistic Regression Employment Type.ipynb` file to train and evaluate the logistic regression model.
4. Execute the `Visualization Practice.ipynb` file to generate visualizations of the dataset.

### Note
- Ensure that the dataset file `AutoInsurance.csv` is placed in the appropriate directory specified in the Python files.
- Adjust file paths and configurations as per your environment and requirements.

Feel free to explore and contribute to this project!
