Project Summary This project explores the application of machine learning algorithms to forecast energy consumption based on historical usage data and environmental features. Accurate energy prediction enables smarter resource allocation, improved operational planning, and enhanced sustainability initiatives. The work is presented through code, a research paper, and an academic presentation.

Motivation and Background With the global push toward energy efficiency and sustainability, the ability to forecast energy consumption accurately is becoming increasingly vital. Traditional forecasting methods struggle with non-linear patterns and high-dimensional data, making machine learning a compelling alternative. This project investigates the effectiveness of different machine learning regression models in addressing this challenge.

Objectives Predict short-term energy consumption using historical and weather-related features. Compare regression models in terms of accuracy and performance. Identify the model that best balances simplicity, interpretability, and accuracy. Present findings in a research- and presentation-ready format.

Dataset Description Features: Temperature, humidity, wind speed, previous energy consumption values. Target: Energy consumption (continuous numerical value). Data Handling: Missing values were handled appropriately. Features were normalized using MinMaxScaler. Dataset was split into training and test sets (80/20).

Methodology 1-Data Preprocessing Cleaning missing values Feature normalization Train-test split

2-Modeling Linear Regression Decision Tree Regressor Random Forest Regressor

3-Evaluation Metrics Mean Squared Error (MSE) Root Mean Squared Error (RMSE) R-squared Score (R²)

4-Visualization Actual vs. predicted plots for model performance comparison

Technologies Used Programming Language: Python 3 Libraries: pandas numpy scikit-learn matplotlib

Results Among the three models tested—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—the Random Forest Regressor delivered the best performance overall. It achieved the lowest Mean Squared Error (MSE) and Root Mean Squared Error (RMSE), indicating higher accuracy in its predictions. Additionally, it scored the highest R² value, demonstrating strong explanatory power. In contrast, Linear Regression performed the worst due to its inability to model the non-linear relationships present in the dataset. The Decision Tree Regressor performed moderately well but was outperformed by the ensemble-based Random Forest. Visualization of actual versus predicted values further supported the conclusion that Random Forest provided the most reliable forecasts.

Included Files MLprojecEtnergy Consumption Forecasting.py: Main Python code for data processing, training, and evaluation. MachinePaper.pdf: Detailed research paper outlining the background, methodology, analysis, and conclusions. MachinePPT.pdf: Presentation slide deck summarizing the project’s key points for academic presentation.

Strengths and Limitations Strengths: Multiple models for performance comparison Easy-to-understand code and methodology Clear presentation and report Meaningful real-world application

Limitations: Dataset details are not deeply analyzed (e.g., correlation analysis missing) No hyperparameter tuning applied Limited number of models explored

Future Improvements Incorporate feature selection and correlation heatmaps Apply hyperparameter tuning using GridSearchCV Test more advanced models (e.g., XGBoost, LSTM for time series) Extend dataset with real-world live feeds (IoT-based consumption logging)

Academic Context This project was developed as part of an academic course at Effat University, Jeddah, Saudi Arabia. It showcases the application of AI and machine learning in solving real-world problems, particularly within the domains of sustainability and intelligent systems.
