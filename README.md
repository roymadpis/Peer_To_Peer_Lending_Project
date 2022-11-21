# Peer_To_Peer_Lending_Project
 In this Python Script we build Peer To Peer Lending Model that advises investors whether or not to invest in a given loan.
The project was conducted as part of a semestrial course in Reichman university in Business & Data Analytics program and got the highest score among 7 teams working on the same project.

The model classifies loans into 2 classes: 
class "0" = The loan will have realized return that is higher than 2%
class "1" = The loan will have realized return that is Not higher than 2%

#### We build the model in 4 different steps
1. Loading the data: loading the cleaned table (Continuing stage 2)

2. Preprocessing:
- Creating new features - Feature engineering
- Selecting columns to use in the model
- Dealing with NAs (if needed)
- Dealing with outliers (if needed)
- One Hot Key encoding
- Last filtering of columns
- Train-Test Split (needs to be done before scaling)
- Scaling - normalizing the data

3. Model selection: Building a XGBoost model

4. Scoring:

- For Classification models:
  - Accuracy, Precision, Recall, F1 Score + NPV (Negative predictive value)
  - ROC Curve + AUC
- Cross validation - In order to make sure our results are valid and weren't influenced by a specific test set, we built a function that enables performing cross vaildation and get the min, max, mean and sd of multiple metrices.

#### Notice that we also performed:
- Feature Selection
- Parameter Optimization
