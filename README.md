# Company-Bankruptcy-Prediction

# Project Summary -
The aim of this project is to develop a predictive model to forecast the likelihood of a company going bankrupt based on historical financial data. The dataset used in this project is sourced from the Taiwan Economic Journal, covering the period from 1999 to 2009, and includes information on various financial attributes of companies listed on the Taiwan Stock Exchange.

The challenge in this project lies in developing a robust predictive model that can accurately identify the minority class instances and overcome the class imbalance issue. The model's performance will be evaluated using appropriate evaluation metrics to assess its effectiveness in predicting bankruptcy.

The successful implementation of this project can have significant implications for financial organizations, business practitioners, investors, and policymakers. By accurately predicting the risk of business failure, informed lending decisions can be made, reducing economic losses and potential impacts on the wider economy.

Throughout the project, various machine learning techniques and algorithms will be explored and evaluated to identify the most effective approach for bankruptcy prediction. The resulting model will provide insights into the financial indicators and patterns that contribute to a company's likelihood of going bankrupt, aiding in proactive risk management and decision-making processes.

# Problem Statement -
The problem at hand is to develop a predictive model that accurately forecasts the likelihood of a company going bankrupt based on historical financial data sourced from the Taiwan Economic Journal. The objective is to overcome the challenge of predicting business failures by analyzing financial indicators and market conditions.

This project has implications for financial organizations, investors, and policymakers, as accurate bankruptcy prediction can support informed decision-making in lending, risk management, and policy formulation. The focus is on building a reliable model that can identify companies at high risk of bankruptcy.

The project involves exploring and evaluating various machine learning algorithms to find the most effective approach for bankruptcy prediction. The model's performance will be assessed using appropriate evaluation metrics.

In summary, the aim of this project is to develop a robust predictive model to forecast business failures, providing valuable insights for financial stakeholders in their decision-making processes.


# Selected Features -
-	Research and development expense rate	
-	Operating Expense Rate	
-	Inventory Turnover Rate (times)	
-	Quick Asset Turnover Rate	
-	Cash Turnover Rate	
-	Total Asset Growth Rate

# Compare the accuracy of the models on the training set -
![image](https://github.com/pratap-vj/Company-Bankruptcy-Prediction/assets/123111274/ca400090-0cda-4e7e-812c-7b988dc6361b)

# ROC - Plotting Graph -
![image](https://github.com/pratap-vj/Company-Bankruptcy-Prediction/assets/123111274/23d8ed2e-fb19-4109-8ec0-61b11c8c8f00)

# Conclusion -
This project aimed to develop a predictive model for company bankruptcy using machine learning techniques. Three models, namely Logistic Regression, Random Forest Classifier, and XgBoost Classifier, were trained and evaluated using various evaluation metrics.

The results of the evaluation showed that the XgBoost Classifier outperformed the other models in terms of accuracy, precision, recall, and F1-score. It achieved the highest accuracy and demonstrated a relatively higher precision for predicting the positive class (bankruptcy) compared to the other models. Although the precision and recall for the positive class were still relatively low, the XgBoost Classifier showed better performance overall.

The selected features, such as continuous interest rate, persistent EPS in the last four seasons, per-share net profit before tax, debt ratio, net worth/assets, borrowing dependency, net profit before tax/paid-in capital, net income to total assets, net income to stockholder's equity, and equity to liability, were found to have significant impact on predicting bankruptcy.

The predictions and insights derived from the bankruptcy prediction model can have valuable applications in various sectors. Companies can use these models to diagnose their current financial status and adjust their strategies accordingly. Business operators can manage their enterprises more effectively by monitoring key indicators that impact the risk of bankruptcy. Investors can modify their investment portfolios by assessing the bankruptcy risk of companies. Governments can implement macroeconomic policies and improve financial regulations based on the predictions of corporate bankruptcy.

In summary, the development of predictive models for company bankruptcy is crucial in the realm of financial analysis. By selecting appropriate methods and accurately forecasting bankruptcy risks, businesses can make informed decisions to mitigate potential financial risks and enhance their financial systems. The global financial crisis and the increasing credit risks further emphasize the importance of this field. Extensive research has been conducted to refine and improve the accuracy of bankruptcy predictions.

Overall, this project contributes to the field of advanced financial analysis by utilizing machine learning algorithms and statistical models to predict company bankruptcy.


