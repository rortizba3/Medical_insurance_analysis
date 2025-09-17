# Medical_insurance_analysis
The goal of this project was to analyze the impact that smoking, BMI (Body Mass Index), age, number of children, and region have on the cost of medical insurance. Simultaneously, insights into the factors most influencing health coverage could be determined. In addition, the project included some guidance geared towards students about regression (Random Forest and Linear Regression) and feature engineering. 

The dataset 'insurance.csv' comes from the Medical Insurance Cost Dataset found on Kaggle. The dataset contained medical insurance cost for 1338 individuals with 7 key attributes: age, sex, bmi, children, smoker, region, and charges. Link to dataset: https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset

## Findings
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/64add378-1e9e-43c4-82d7-39179a05902e" />

<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/f7f4fb04-08ed-4a4d-93d9-41aaf7fb1d8d" />

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b7a7e5cc-8862-4561-8441-f8d754147662" />

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b0278ca0-22c8-484a-a0b7-247d5163d7a3" />

## Data Analysis
* Smokers incur significantly higher medical charges compared to non-smokers, as clearly indicated by the box plot and the strong feature importance of 'smoker\_yes' in the Random Forest model.
* BMI and age are also significant factors influencing medical charges, with higher values generally correlating with increased costs.
* The Random Forest Regressor model demonstrated better performance in predicting medical charges compared to the Linear Regression model, achieving a higher R-squared value (0.82 vs 0.74) and lower MAE (2769.16 vs 4122.80). 
* Regional differences and the number of children have a less significant impact on medical charges compared to smoking status, age, and BMI, according to the Random Forest feature importances.

## Insights
* The substantial impact of smoking on medical costs suggests that public health initiatives focused on smoking cessation could be highly effective in reducing healthcare expenditures and improving affordability.
* Further analysis into the interaction effects between factors like smoking and BMI could provide deeper insights into the complex drivers of high medical costs.
* Programs that highlight how smoker status and BMI affect medical insurance costs for current, newly enrolled, and prospective policyholders can promote transparency in coverage and educate individuals on the dual benefits of quitting smoking and improving BMI: reduced healthcare expenses and better health outcomes.
