# Crop Recommendation System

<p align="center">
  <img src="https://media.licdn.com/dms/image/v2/C5112AQE6dfRzV3EJtA/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1557787805799?e=2147483647&v=beta&t=_39DGiXh7r60pFpJAvHludTyFR4MraCanL2SS7u2xrU" alt="Crop Recommendation System">
</p>

## Overview
[Crop Recommendation System](https://gamma.app/docs/Crop-Recommendation-System-Data-Driven-Agriculture-ojcotievaiovhth?mode=doc): Data-Driven Agriculture. A solution designed to provide farmers with personalized recommendations for crop selection based on data analysis and machine learning.

Crop Recommendation Dataset: [Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

## Data Collection and Preprocessing

- Data Gathering
-- We collected comprehensive datasets from Kaggle, including soil parameters and crop yields.
- Cleaning and Preprocessing
-- Python libraries like Pandas and NumPy were used to clean and structure the data.
- Feature Engineering
-- We engineered relevant features to enhance the predictive power of our models.
  
## Machine Learning Models

- Content-Based Filtering
-- This approach recommends crops based on soil and climate attributes using cosine similarity.
- Collaborative Filtering
-- We implemented matrix factorization using SVD to predict crop-environment interactions.
- Performance Evaluation
-- Our models achieved high accuracy, with precision and recall exceeding 0.95 across classes.

## Model Training and Validation

- Feature Transformation
-- We applied encoding and scaling techniques to prepare our features for modeling.
- Train-Test Split
-- Data was split into training, testing, and validation sets to ensure robust evaluation.
- Iterative Refinement
-- Multiple iterations of training and validation improved our model's performance and generalization.

## MLOps Integration

- Model Versioning
-- MLflow tracks different versions of our recommendation models, ensuring reproducibility.
- Performance Monitoring
-- Continuous monitoring of model metrics helps identify drift and trigger retraining.
- Deployment Pipeline
-- Automated deployment pipelines streamline the process of updating models in production.

## Advanced Techniques - GANs

- Synthetic Data Generation
-- GANs create realistic synthetic crop profiles to augment our training data.
- Enhanced Recommendations
-- GAN-generated profiles improve the robustness of our recommendation system.
- Edge Case Handling
-- Synthetic data helps our model handle rare or unseen crop-environment combinations.

## Data Augmentation with GANs

- Augmented Dataset Creation
-- Utilize GANs to generate diverse and realistic synthetic profiles for expanding our training dataset.
- Recommendation System Integration
-- Incorporate synthetic data seamlessly into our recommendation system to enhance predictive capabilities.

## Contributors
> Mostafa Mohamed Youssef |
> Hanin Essam Sayed |
> [Abdelrhman Walaa](https://github.com/AbdelrhmanWalaa) |
> Abdelrahman Osama Nabih






