# Movie Recommendation with PySpark Big Data

This project involves building a movie recommendation system using PySpark, specifically focusing on handling vast amounts of data and implementing Collaborative Filtering with the ALS model.

## Overview

The dataset used for this project comprises 25 million ratings given to 62,000 movies by 162,000 user IDs. The primary objectives revolve around Exploratory Data Analysis (EDA) using Spark SQL and implementing Collaborative Filtering to generate movie recommendations.

## Key Highlights

1. **Exploratory Data Analysis (EDA)**
    - Utilized Spark SQL for efficient handling and analysis of the massive dataset.
    - Explored various aspects of the data, including user behavior, movie statistics, and rating distributions.

2. **Collaborative Filtering with ALS Model**
    - Preprocessed the data for model input, ensuring data quality and integrity.
    - Implemented Collaborative Filtering using the ALS (Alternating Least Squares) model.
    - Achieved an RMSE (Root Mean Squared Error) of 0.81 on the preprocessed dataset, showcasing the model's predictive accuracy.

## Project Structure

- **`data/`**: Contains the dataset used for analysis and model training.
- **`notebooks/`**: Jupyter notebooks illustrating the EDA process, data preprocessing, and model implementation.
- **`scripts/`**: Python scripts for specific functions/modules used in the project.
- **`results/`**: Holds the output, including model evaluation metrics and recommended movie lists.

## Getting Started

To replicate and explore this project locally, follow these steps:

1. **Clone the Repository:**
   ```
   git clone https://github.com/your-username/movie-recommendation-pyspark.git
   ```

2. **Setup Environment:**
   - Ensure Python and necessary dependencies are installed (requirements provided in `requirements.txt`).
   - Set up PySpark environment or use a cloud-based Spark platform (e.g., Databricks, Google Colab).

3. **Explore the Notebooks:**
   - Navigate to `notebooks/` and open Jupyter notebooks to delve into the EDA and model implementation process.
   
4. **Run Scripts:**
   - Experiment with different parameters or preprocessing steps by modifying the provided scripts in the `scripts/` directory.

## Results and Conclusion

The project showcases the power of PySpark in handling large-scale data for recommendation systems. Achieving an RMSE of 0.81 demonstrates the effectiveness of Collaborative Filtering in predicting user preferences for movies.

Feel free to explore the codebase, datasets, and methodologies to gain insights into movie recommendation systems using PySpark.

---

Feel free to add specific installation instructions, prerequisites, or any additional details that might be relevant to users exploring your project!
