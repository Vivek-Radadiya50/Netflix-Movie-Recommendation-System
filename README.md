# Netflix Movie Recommendation System

## 1. About the Dataset
This project involves developing a recommendation system for Netflix movies using collaborative filtering techniques. The dataset includes user-movie ratings and metadata, which are used to enhance personalized recommendations and address the cold start problem in the recommendation process.

## 2. Objective
The primary objectives of this project are to:
- Enhance personalized movie recommendations by addressing the cold start problem.
- Utilize user-movie rating similarities to improve recommendation accuracy.
- Develop an ensemble model to optimize recommendation performance.

## 3. Approach
The project employs the following approach:
- **Data Preparation:**
  - Created a Compressed Sparse Row (CSR) matrix for efficient storage and manipulation of the ratings data.
  - Generated features using user, movie, and global ratings to build a robust recommendation model.
  - Implemented measures to prevent data leakage and ensure the integrity of the evaluation process.
- **Model Development:**
  - Applied Singular Value Decomposition (SVD) matrix factorization using the Surprise library to capture latent factors in the rating data.
  - Developed an ensemble stacking model using XGBoost to combine multiple predictive features and improve performance.
- **Evaluation & Optimization:**
  - Evaluated feature importance and identified key performance indicators (KPIs) to measure the effectiveness of the recommendation system.
  - Used hyperparameter tuning with cross-validation to refine the models and enhance accuracy.

## 4. Results & Key Features
- **Performance:** Achieved an RMSE (Root Mean Squared Error) of 1.072, indicating a strong performance in predicting movie ratings.
- **Model Features:** Utilized SVD predictions and baseline models from the Surprise library as features in the ensemble stacking model.

## 5. License
This project is licensed under the MIT License.

## 6. Contact
For any questions or feedback regarding this project, please contact:
- **Vivek Radadiya**
