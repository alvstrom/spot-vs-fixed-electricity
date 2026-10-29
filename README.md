# Spot vs fixed electricity

Final project for the Decision Support Systems course.

A decision support system that predicts whether a household would pay less with a spot price or a fixed price electricity contract, based only on its usage habits.

Data
- Smart meter data from about 1000 London households (2013), Low Carbon London project
- Finnish spot prices for 2024 from Elering's API

Methods
- ETL, EDA and variance analysis
- Min-max normalization and one-hot encoding
- Decision tree (Gini, entropy, max_depth, min_samples_split) and KNN
- Confusion matrices, fairness (error rate balance, predictive parity), cold start and popularity bias

Results
- Decision tree 77% and KNN 81% test accuracy, vs 73% for a simple rule and 50% for guessing
- Night-time use was the most important feature

The notebook runs in Google Colab. The first run downloads the data and takes about 10 minutes.
