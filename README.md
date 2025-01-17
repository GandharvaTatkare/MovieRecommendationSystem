# Movie Recommendation System

This repository contains the implementation of a movie recommendation system that predicts if a movie belongs to a desired genre. The project uses the TMDB 5000 Movie Dataset from Huggine Face Library, vectorization techniques, and machine learning models for prediction.

## Dataset

- **Source**: Hugging Face TMDB 5000 Movie Dataset
- **Structure**: Cleaned JSON dataset with information on movie genres, plots, and other metadata.

## Features

1. **Data Cleaning**:
   - Cleaned the JSON dataset for better usability and ensured compatibility with the machine learning pipeline.

2. **Genre Prediction**:
   - Utilized **TF-IDF Vectorization** to process movie plot summaries.
   - Built a **Logistic Regression** model to predict if a movie fits a desired input genre category.

3. **Web Scraping for Movie Plots**:
   - Explored multiple methods to fetch movie plots from their respective Wikipedia pages.
   - Successfully implemented web scraping using **Beautiful Soup**.

## Project Files

- **`Movie_Recommendation.ipynb`**: Jupyter Notebook containing the full implementation of the project. Contains backend functions for Movie plot extraction through wikipedia

## Future Improvements

**Docker Implementation:**

- Create a Dockerized pipeline for the project to automate the workflow.
- Schedule periodic data updates and model retraining using tools like Cron or Apache Airflow within the Docker environment.

**Model Deployment:**
- Deploy the model as a fully functional REST API using frameworks like Flask or FastAPI.
- Host the API on cloud platforms such as AWS, Google Cloud, or Azure for scalability and real-time recommendations.

**Interactive Front-End:**
- Build a user-friendly front-end interface for seamless interaction with the recommendation system.
- Use frameworks like React or Vue.js for enhanced UI/UX.

**Enhanced Model:**
- Experiment with advanced deep learning models like Transformers (e.g., BERT) for improved genre classification accuracy.
