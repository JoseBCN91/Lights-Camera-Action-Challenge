# Lights, Camera, Action Challenge 🎥

Welcome to the Lights, Camera, Action Challenge! This project is a thrilling competition where we dive into the world of movies and TV shows, predicting the IMDB scores like seasoned film critics.

## Objective

The objective of this challenge is to predict the IMDB score for test titles using the provided dataset. The IMDB score is a well-established metric in the film industry, serving as a barometer for a title's quality. The scores are transformed into target classes using the get_imdb_score_class function provided in the dataset.

## Dataset

The dataset consists of four CSV files: `train_titles.csv`, `train_credits.csv`, `test_titles.csv`, and `test_credits.csv`.

- `train_titles.csv` and `test_titles.csv` contain information about the titles, such as the title name, type (movie or show), description, release year, age certification, runtime, genres, production countries, streaming platform, IMDB votes, IMDB score, and target class.

- `train_credits.csv` and `test_credits.csv` provide extra information about the actors and directors of each title.

## Preprocessing and Training

The data preprocessing steps include handling missing values, transforming the 'genres' column into binary features, encoding categorical predictors, and splitting the data into training and validation sets.

We use linear regression as our model to predict the IMDB scores directly. Regression evaluation metrics like Mean Absolute Error (MAE) and R^2 score are used to assess the model's performance.

## Evaluation

The performance of the model is evaluated using regression metrics, including MAE and RMAE, on the validation set, as well as an f1-macro on the test set.

Happy coding! 🚀🎬

