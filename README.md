![Motor Insurance](https://www.servicenow.com/workflow/it-transformation/nationwide-insurance-digital-transformation/)
# Final-Capstone-Project-Machine-Learning
Motor_insurance_claim_Prediction Using ML
# Abstract:
>### The goal of this project is to develop a machine learning model that predicts the claim amount for Motor insurance based on various features. By accurately estimating the claim amount, insurance companies can better manage their risk and make informed decisions.
# Content:
>### The problem addressed is predicting the claim amount for Motor Insurance using machine learning algorithms. The aim is to build a model that accurately predicts the claim amount based on various customer and policy-related features. The model should be able to analyze the given features and provide an estimation of the expected claim amount for an insurance policy.
## Study of Existing Systems:
>### An analysis of existing systems for Motor Insurance claim prediction reveals that traditional methods often rely on manual assessment and expert judgment, leading to subjective and potentially inaccurate claim estimations. There is a need for a data-driven approach that leverages machine learning techniques to improve the accuracy and efficiency of claim amount predictions.
## Identification of Gaps in Existing Systems:
>### Existing systems lack the ability to quantitatively estimate the claim amount based on various factors and features associated with the customer and policy. The reliance on manual assessment introduces subjectivity and inconsistency in claim estimations. Additionally, traditional methods may not effectively capture the complex relationships and patterns within the data, resulting in suboptimal predictions.
## Proposed Solution:
>### The proposed solution involves developing a machine learning model that utilizes the available features such as customer demographics, policy details, and historical claim data to predict the claim amount accurately. By leveraging advanced algorithms and techniques, the model aims to uncover patterns, relationships, and dependencies within the data to make reliable predictions.
## Main Objective:
>### The main objective of this project is to build a robust and accurate machine learning model that can predict the claim amount for Motor Insurance policies. By accurately estimating the claim amount, insurance companies can better manage their claims processing, assess risk, and allocate resources effectively.
## Data Description:
The dataset used in this project consists of historical data related to Motor insurance claims. It contains information about different features such as the policy holder's vehicle information, policy details, and previous claim history. The target variable is the claim amount, which represents the monetary value of the insurance claim.
## Tools used to implement proposed solution:
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Sklearn
- Jupyter Notebook
## Features:
> The features used for predicting the claim amount include:
> Customer-related features:

- Customer: The "Customer" column represents the unique ID of each customer in the dataset.
- Country: The country where the customer is located.
- State Code: The code representing the state where the customer resides.
- State: The state where the customer is located.
- Education: The educational background of the customer.
- EmploymentStatus: The employment status of the customer.
- Gender: The gender of the customer.
- Income: The annual income of the customer.
- Marital Status: The marital status of the customer.

> Policy-related features:
- Response: The "Response" column in the dataset refers to whether the customer is satisfied with the claim amount or not
- Coverage: The type of coverage provided by the insurance policy.
- Location Code: The code representing the location of the insured vehicle.
- Monthly Premium Auto: The monthly premium amount paid by the customer.
- Months Since Last Claim: The number of months since the last insurance claim was made.
- Months Since Policy Inception: The number of months since the policy was initiated.
- Number of Open Complaints: The number of open complaints registered by the customer.
- Number of Policies: The number of insurance policies held by the customer.
- Policy Type: The type of insurance policy.
- Policy: The specific policy identifier.
- Claim Reason: The "Claim Reason" variable refers to the reason or cause behind the insurance claim.
- Sales Channel: The channel through which the insurance policy was sold.
- Total Claim Amount: The "Total Claim Amount" variable refers to the total amount claimed by the customer in their insurance claim.
- Vehicle Class: The class of the insured vehicle.
- Vehicle Size: The size category of the insured vehicle.
## Conclusion:

- Based on the analysis and evaluation of different regression models for predicting motor insurance claims, the Random Forest model stands out as the top performer. It achieves a high training accuracy of 99.46% and a test accuracy of 95.91%, indicating its ability to accurately predict claim amounts both on the data it was trained on and on new, unseen data.

- The Gradient Boosting Regressor model also demonstrates strong performance, with a training accuracy of 96.68% and a test accuracy of 95.88%. While it performs slightly lower than the Random Forest model, it still shows good predictive capability and generalization.

- Therefore, the final conclusion is that the Random Forest model is the recommended choice for predicting motor insurance claims.
