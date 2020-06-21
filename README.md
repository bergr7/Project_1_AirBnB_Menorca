# Project_1_AirBnB_Menorca
AirBnB accommodations in Menorca (2020-2021)

Link to Medium Post: https://medium.com/@bernardogarciadelrio/fancy-a-trip-to-menorca-a7e6e12056ba

## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Results
5. Licensing, Authors, Acknowledgements

## Installation
- Libraries including in Anaconda distribution of Python.
- Category_encoders 2.2.2 libraries - Description and Anaconda installation instructions at this link: https://anaconda.org/conda-forge/category_encoders
- XGBoost model - Description and Anaconda installation instructions at this link: https://anaconda.org/conda-forge/xgboost

## Project Motivation
I was interested in using publicly available datasets of AirBnB accommodations in Menorca from May 2020 to May 2021 to understand how AirBnB market behaves in Menorca and if, with the data available, there is any promising ML model to predict average prices for a new listing. I posed the following questions:

1. What is on average the summer price increase of AirBnB accomodations in Menorca?
2. Can someone overnight in Menorca for less than 35 USD in any of season? If so, in which neighbourhood adn type of accoommodation?
3. Compare a Decision Tree, Random Forest and Gradient Boost ML models to predict AirBnB accommodations average prices in Menorca. Which one is more promising?

This project is part of the Udacity Nanodegree online course.

## File Descriptions
The code is run on a Jupyter Notebook called **Project 1.ipynb**. Several comments and Markdown cells have been added so the logic can be followed thourghout the process of answering the aforementioned questions.

There are 3 datasets used in this project in .csv files:

- **calendar.csv**: Detailed Calendar data for listings in Menorca
- **listings.csv**: Detailed Listings data for Menorca
- **listings_summary.csv**: Summary information and metrics for listings in Menorca. (File originally called listings.csv on website)

The data was compiled the 30th April 2020 and downloaded from http://insideairbnb.com/get-the-data.html

## Results
The main findings of the code are summary in a post published on Medium. It can be found here***

## Licensing, Authors, Acknowledgements
I would like to give credit to:

- Inside AirBnB for making real data publicly avaialable
- Aurélien Géron for the structures given his book Hands-On Machine Learning with Scikit-Learn & Tensorflow
- Stackoverflow community for making code questions and answers publicly available
- Udacity Nanodegree tutors for providing valuable lessons and being available to answer questions
