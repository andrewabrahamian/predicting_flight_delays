## Predicting Flight Delays for Airline Carriers
#### Authors: Andrew Abrahamian, Antonio Martinez, Mohammad Kanawati, Reed Evans
#### MIDS W261: Machine Learning at Scale | Spring 2024 | Final Project

Our project focuses on developing a machine-learning model to predict flight delays, with the goal of enhancing operational efficiencies within the airline industry. We approach this as a classification problem, defining flight delays based on the FAA's criteria of departures occurring 15 minutes after scheduled time. The primary objective is to minimize the False Negative rate (predicting no delay when there actually is one), measured by recall.

Using a joined dataset combining On-Time Performance & Weather (OTPW) sourced from the Department of Transportation (DOT) and the National Oceanic & Atmospheric Administration (NOAA), we trained and evaluated several models. These include Logistic Regression, XGBoost, and Random Forest (RF), all optimized to maximize recall due to the imbalance in our sample (only 17.9% of flights classified as delayed).

In our final phase, we compared the performance of these models on a five-year dataset. The logistic regression baseline model achieved a recall of 82.6% and an F2 score of 81.8%, outperforming the more complex tree-based models in our specific context.

Based on our findings, we recommend deploying the logistic regression model due to its strong performance, interpretability, and cost-effectiveness for integration into existing operational processes. We propose a phased implementation strategy, starting with a subset of airline carriers and routes, and scaling up as improvements in delay prediction lead to enhanced operating margins.

Future iterations should explore hyperparameter tuning for tree-based models and additional feature engineering to further refine and scale model performance.

This approach promises significant cost savings and operational benefits for US-based airline carriers, maximizing profitability and customer value.