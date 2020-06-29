# Project Overview
Capstone Project for Udacity Data Science Nanodegree

Data for this project is sourced from the Taarifa waterpoints dashboard, which aggregates data from the Tanzania Ministry of Water. It is hosted by DRIVENDATA as an open source project aimed at tackling social challenges with Data Science. https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/

The goal of the project is to effectively predict the operating condition of a water front for each record in the data. Each record or waterfront has 30+ features associated with it.

## The Data
There are 3 files used for the analyses:
**labels.csv:** depicts whether a waterfront is funtional, not functional, or functional needs repair
**values.csv:** contains fields for all the features of the waterfronts
**competition_test.csv:** features used in predicting water table status with predictions submitted on the competition site

## Steps Taken
- Data Exploration
- Feature selection 
- Dealing with missing values
- Dimensionality reduction (TruncatedSVD)
- Classification Pipeline
- Model Evaluation
- Competition Prediction Submissions
