# Movie Recommendation

This repository contains a simple movie recommendation system using Python and the scikit-learn library. The system is based on content-based filtering, which recommends movies to users based on the similarity of movie features. In this project, we use a dataset of movies to demonstrate the recommendation process.

## Table of Contents
- [Project Overview](#project-overview)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)

## Project Overview

This movie recommendation system is designed to help users discover movies similar to the ones they like. It utilizes natural language processing techniques to analyze movie metadata such as keywords, cast, genres, and directors to make recommendations.

The key steps in the recommendation process include:
1. Reading a movie dataset from a CSV file.
2. Selecting relevant features for recommendation, such as keywords, cast, genres, and director.
3. Creating a combined feature that encapsulates the selected features for each movie.
4. Constructing a count matrix from the combined features.
5. Calculating cosine similarity between movies based on the count matrix.
6. Taking user input to specify a movie they like.
7. Finding movies with the highest similarity to the user's input.
8. Presenting a list of recommended movies.

## Getting Started

To run the movie recommendation system locally, follow these steps:

1. Clone this repository to your local machine:


2. Install the required Python libraries:

   ```bash
   pip install pandas numpy scikit-learn
   ```

3. Download the movie dataset CSV file and place it in the project directory. Make sure the file is named "movie_dataset.csv."

4. Run the recommendation system script:

   ```bash
   python movie_recommendation.py
   ```

5. Follow the on-screen instructions to input a movie you like, and the system will provide movie recommendations based on your input.

## Dependencies

This project uses the following Python libraries:

- pandas
- numpy
- scikit-learn

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn
```

## Usage

To use the movie recommendation system, run the Python script `movie_recommendation.py` as explained in the "Getting Started" section. The script will guide you through the process of entering a movie you like and provide you with a list of recommended movies based on the content-based filtering algorithm.
