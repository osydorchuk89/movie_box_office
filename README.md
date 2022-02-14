# Analyzing 5,000 highest-grossing movies and predicting their revenue

## Summary
* Collected data about 5,000 highest-grossing movies
* Explored the dataset to identify which movie features are related to their revenue
* Built a model that predicts a movie revenue based on some of its features
* Published an article on Medium summarizing key results of the analysis

## Project structure
The project is divided into two Jupyter notebooks:
* movies_data_collection.ipynb - collecting the data about the movies and creating a dataset
* movies_data_analysis.ipynb - analyzing the data and predicting movie revenue

The datatests used:
* data/movies.csv - the original dataset collected from the [TMDB website](https://www.themoviedb.org/) using its API
* data/movies_kaggle.csv - the additional dataset by Daniel Grijalva available on [Kaggle](https://www.kaggle.com/danielgrijalvas/movies)
* data/languages.csv - the dataset with language ISO codes taken from [datahub.io](https://datahub.io/core/language-codes)

## Packages
Python Version: 3.9.7

To install all necessary packages, run `pip install -r requirements.txt`

## Licensing
The code is released under the [MIT License](https://github.com/osydorchuk89/movie_box_office/blob/main/LICENSE).

## Acknowledgement
This project was created for the Udacity Data Scientist Nanodegree program.
