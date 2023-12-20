# Energy-Prediction-for-House-Energy-Consumption

The "Energy Prediction Model for House Energy Consumption Optimization" project aimed to create a robust machine learning solution to forecast a house's energy usage based on various environmental factors such as temperature, humidity, wind, pressure, and more. The project encompassed several key phases:

Objective:
To develop a predictive model for optimizing house energy consumption through machine learning techniques.

### Methodology:

Data Exploration and Feature Selection:
Conducted comprehensive data exploration to understand the dataset's characteristics.
Performed correlation analysis to identify the most influential features impacting energy consumption.

Model Development:
Utilized a range of machine learning algorithms, including Logistic Regression, Naive Bayes, KNN, Decision Tree, Random Forest, Support Vector Classification (SVC), Gradient Boosting, XGBoost, and Multilayer Perceptron (MLP).
Each algorithm was implemented and evaluated to gauge its performance in predicting energy usage.

Model Evaluation and Comparison:
Evaluated model performance using various metrics, focusing on accuracy, precision, recall, and F1-score.
Constructed Receiver Operating Characteristic (ROC) curves and calculated Area Under the Curve (AUC) scores for all algorithms.
Visualized the ROC curves with AUC scores in a single graph for easy comparison between models.

Optimization and Final Model Selection:
Employed hyperparameter tuning techniques, specifically GridSearchCV, to fine-tune the Support Vector Classification (SVC) model with RBF Kernel.
Ensured the highest predictive accuracy (89%) while actively avoiding overfitting issues.

Achievements and Results:
Accuracy: Achieved a significant accuracy rate of 89%.
Model Selection: The optimized SVC model with RBF Kernel was chosen as the most effective for energy usage prediction.
Avoidance of Overfitting: Ensured the model's robustness by actively mitigating overfitting concerns during the tuning phase.

Conclusion:
The project successfully developed a predictive model using machine learning that accurately forecasts house energy consumption based on environmental parameters. The optimization process, particularly the careful selection of features and hyperparameter tuning, resulted in an efficient model with high accuracy, contributing to the potential for better energy management and optimization in residential settings.






