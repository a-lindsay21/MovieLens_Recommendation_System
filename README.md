# MovieLens Recommendation System

## Project Overview
This project explores the development of a robust movie recommendation system using the MovieLens dataset. The system implements and evaluates collaborative filtering, content-based filtering, and a hybrid recommendation model to deliver personalized movie suggestions. The hybrid model, leveraging both user preferences and content attributes, demonstrated superior precision, making it the most effective approach.

## Key Features
- **Dataset Analysis**: Comprehensive analysis of 100,836 user ratings, 9,742 movies, and user-generated tags.
- **Recommendation Algorithms**:
  - Collaborative Filtering using SVD.
  - Content-Based Filtering using movie metadata.
  - Hybrid Model combining collaborative and content-based techniques.
- **Evaluation Metrics**:
  - RMSE for Collaborative Filtering: **0.8818**
  - Precision@10 for Hybrid Model: **1.0**

## Visualizations
- Distribution of Ratings.
- Evaluation Metrics: RMSE and Precision@10.
- Recommendations: Top movies for User 414 and similar users.

## Technologies Used
- **Python**: Data processing and algorithm implementation.
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation.
  - `scikit-learn`: Content-based filtering.
  - `scikit-surprise`: Collaborative filtering.
  - `matplotlib`, `seaborn`: Data visualization.
- **Dataset Source**: [MovieLens Dataset](https://www.kaggle.com/datasets/aigamer/movie-lens-dataset).

## **License**
This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/).

### **What This Means:**
1. **You Are Free To:**
   - **Use** the project for personal or commercial purposes.
   - **Share** the project (e.g., redistribute it) in its original, unmodified form.

2. **You Cannot:**
   - **Modify** the project, including creating derivative works.
   - **Use** the project in a way that suggests endorsement by the original author.

3. **Attribution Required:**
   - You must give appropriate credit to the author.
   - Provide a link to the license in any shared copies of the work.

4. **No Warranty or Liability:**
   - The project is provided \"as is\" without any warranties.
   - The author is not liable for any damages or issues arising from the use of the project.

### **Why This License?**
This license ensures that the project can be freely used and shared while protecting the original work from unauthorized modifications. It is ideal for individuals who want to maintain the integrity of their work while allowing others to benefit from it.
