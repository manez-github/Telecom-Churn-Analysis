# Telecom Customer Churn Analysis

## Project Overview
This project analyzes customer churn in a telecommunications company to identify patterns and factors that contribute to customer attrition. The analysis helps understand why customers leave the service and provides insights for customer retention strategies.

## Dataset Description
The dataset contains information about telecom customers including:
- Customer demographics (gender, senior citizen status)
- Account information (tenure, contract type, payment method)
- Services subscribed (phone, internet, streaming, online security, online backup, device protection, multiple lines)
- Billing information (monthly charges, total charges, payment method, paperless billing)
- Tech Support 
- Churn status

Total Records: 7043 customers
Features: 21 columns

## Technologies Used
- Python 3.12.6
- Libraries:
  - Pandas
  - Matplotlib 
  - Seaborn 

## Key Findings
### Customer Tenure and Churn:

- **Longer-term Customers**: Customers who have been with the company for a significant period are less likely to churn.
- **Short-term Customers**: Customers who have been with the company for a short period (1-2 months) are more prone to churn.

### Contract Type and Churn:

- **Month-to-Month Contracts**: Customers on month-to-month contracts are more likely to churn compared to those on annual or two-year contracts.

### Demographic Factors and Churn:

- **Senior Citizens**: Senior citizens are more likely to churn.

### Service Usage and Churn:

- **Phone Service**: Customers with phone service are more likely to churn.
- **Multiple Lines**: While the difference is subtle, customers with multiple lines are slightly more likely to churn (28.6%) compared to those without (25%).

### Internet Service:

- **Fiber Optic Internet Service**: A significant portion (41.9%) of customers with Fiber Optic internet service have churned.
- **DSL Internet Service**: A smaller portion (19%) of customers with DSL internet service have churned.

### Additional Services:
- **Online Security**: Customers who do not subscribe to Online Security are significantly more likely to churn.
- **Online Backup**: Customers who do not subscribe to Online Backup are more likely to churn.
- **Device Protection**: Customers who do not subscribe to Device Protection are more likely to churn.
- **Tech Support**: Customers who do not subscribe to Tech Support are more likely to churn.
- **Streaming TV**: While the difference is not significant, customers who subscribe to Streaming TV are slightly less likely to churn (30%) compared to those who don't (33.5%).
- **Streaming Movies**: While the difference is not significant, customers who subscribe to Streaming Movies are slightly less likely to churn (29.9%) compared to those who don't (33.7%).

### Billing and Payment Factors:

- **Paperless Billing**: Customers who have opted for paperless billing are more likely to churn.
- **Payment Method**: Customers who pay via Electronic Check are more likely to churn compared to other payment methods.

## How to Use
1. Clone this repository or install the zip file
2. Install required dependencies:
    ```Python 
    pip install pandas matplotlib seaborn
    ```
3. Open and run the Jupyter notebook

## Contributing
Feel free to fork this project and submit pull requests with improvements.

## Suggestions for Improving Services

### Customer Tenure and Churn:

- The company can offer `Introductory Deals` and emphasize on `Long Term Benefits` of staying with the company.

### Demographic Factors:

- The company should tailor its services and communication to the specific needs of senior citizens, perhaps by offering `Dedicated Plans` or `Dedicated Customer Support`.

### Service Usage and Churn:

- The company should analyze the reasons why customers with phone service are more likely to churn and take steps to address these issues, such as `Improving Service Quality`, `Improving Voice Quality`, `Improving Range of Signals`, etc.

### Internet Service:

- Fiber Optic internet service is the most popular among cutomers nowadays because of the high speed of internet service it offers. People will most likely buy Fiber Optic Internet connections if they want a reliable internet service. My analysis strongly recommends `Improvement in Fiber Optic Internet Service` that the company offers.

### Additional Services:

- I strongly recommend to `Spread More Awareness` regarding `Online Security`, `Online Backup` and `Device Protection` as people who have subscribed to these services are more likely to stay with the company.
- My analysis states that the company should `Improve` its `Technical Support`.

### Billing and Payment:

- I do recommend to improve the Paperless Billing services as the people who are using the paperless billing service are more likely to churn out.
- `Improving Electronic Check Payment Method` is `Recommended` as the customers who use electronic check are more likely to churn out.

### Contract Type and Churn:

- `Improve Overall Performance` of the services which will make the customers stay for a longer period of time.

