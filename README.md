Online Shopper Intent and Purchase Prediction
This project focuses on analyzing e-commerce visitor data to predict whether a website session will result in a purchase (Revenue). By understanding user behavior through session metrics, businesses can better target potential customers and improve conversion rates.

Project Files
5.ipynb: The comprehensive Jupyter Notebook containing the data science workflow, including data exploration, feature engineering, and predictive model deployment.

5.csv: The dataset containing 12,330 sessions, including features like administrative pages visited, durations, bounce rates, exit rates, and the target "Revenue" variable.

5.png: A visualization chart showing feature correlations or model performance metrics.

Core Objectives
Behavioral Analysis: Investigating how different page types (Administrative, Informational, Product Related) and their durations influence purchasing intent.

Intent Prediction: Building a machine learning classifier to distinguish between "Likely to Purchase" and "Unlikely to Purchase" sessions.

Probability Scoring: Implementing a probability-based output to assess the confidence of a conversion for individual sessions.

Temporal Insights: Analyzing the impact of specific months, special days (like Mother's Day), and weekends on shopping behavior.

Technical Implementation
Data Preprocessing: Handling categorical variables such as "Month" and "VisitorType" and normalizing numerical features for better model performance.

Feature Importance: Identifying "PageValues" as a critical indicator of customer conversion.

Libraries Used:

pandas (Data processing)

scikit-learn (Machine Learning and Scaling)

matplotlib and seaborn (Statistical visualization)

How to Run
Environment Setup:
Install the required dependencies:

Bash
pip install pandas scikit-learn matplotlib seaborn
Execution:
Open and run the 5.ipynb notebook. The script includes a "Predictive System" section where you can input new session data to receive an instant purchase probability score.

Key Insights
The model effectively filters high-intent traffic from casual browsers, allowing for data-driven decisions in real-time personalization and targeted advertising.
