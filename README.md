# OIL-BEARING-ZONE-PREDICTION-AI-
A Geo-AI project that uses synthetic seismic attributes to classify potential oil-bearing zones. The dataset is generated using basic geophysical rules, and a Random Forest model is trained to detect oil vs non-oil regions. Includes visualizations, feature importance, and evaluation.

Oil-Bearing Zone Detection using Machine Learning

This project explores how seismic attributes can be used to detect possible oil-bearing zones using a simple machine learning workflow. I created a small synthetic dataset that mimics basic subsurface behavior and used a Random Forest classifier to distinguish between oil and non-oil regions. The idea behind this project is to understand how AI can support decision-making in petroleum exploration in an easy and experimental setup.

What This Project Uses

Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Random Forest Classifier

Seismic attributes used: amplitude, frequency, impedance, density, and seismic velocity.

Methodology

I created a synthetic dataset of 1000 samples using realistic geological ranges for seismic attributes. A simple geophysical rule was applied: high impedance, higher amplitude, and slightly lower frequency are more likely to indicate oil-bearing zones. This became the target label for the classification model.

The data was split into training and testing sets. A Random Forest model was trained to learn these relationships. The goal was not to build a perfect model, but to check whether an ML algorithm can capture basic seismic patterns. Once the model was trained, I evaluated its accuracy and generated feature importance to see which attributes influenced the prediction the most.

To better understand the dataset, I added visualizations such as a correlation heatmap, a feature importance plot, and an impedance–amplitude scatter plot showing oil vs non-oil clusters.

Results

The model performed well on the synthetic dataset and correctly identified the simple geological rule used to label oil-bearing zones. Impedance showed strong influence, which matches general reservoir characterization expectations. The scatter plots show clear clusters for oil-bearing vs non-oil points.

Future Work

Use real seismic or well-log datasets
Add geological noise to make the dataset more realistic
Try XGBoost, gradient boosting, or a small neural network
Add cross-plots typically used in geophysical interpretation
Create a dashboard for interactive seismic visualization

AuthoR
BIKRANT KUMAR MISHRA

Bikrant Kumar Mishra
Geo-AI Research | B.Sc Geology
Interested in seismic interpretation, reservoir AI, and petroleum exploration
