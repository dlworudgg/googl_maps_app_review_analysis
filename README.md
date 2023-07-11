# Google Maps App Review Analysis

## Objective

The main objective of this project is to analyze the reviews of the Google Maps app and identify common negative comments. These insights can be used to understand user pain points and inform product enhancements.

## Overview

This repository contains a Jupyter notebook that conducts an analysis of Google Maps app reviews. The reviews are processed and then analyzed using a GPT model from Open AI API and K-means clustering.

## Steps

1. **Data Retrieval**: The data used is loaded from a CSV file which contains Google Maps app reviews.

2. **Data Processing**: The reviews data is cleaned and formatted for further analysis.

3. **Embedding with GPT Model**: The reviews are embedded using a GPT-3 model from OpenAI. This step converts the reviews into a form that can be used for further analysis.

4. **Clustering Google Maps App Reviews**: The reviews are then clustered using K-means clustering. This groups reviews based on their similarity.

5. **Evaluating and Adjusting Clustering**: The clusters are evaluated and possibly adjusted. The analysis initially creates 100 clusters, which are manually reduced to 40 clusters.

6. **Review Analysis**: The notebook then dives into analyzing specific aspects of the reviews, focusing on negative reviews related to saved places and the review system of the Google Maps app.

## Requirements

To run this notebook, you'll need Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- openai
- requests
- tqdm
- tenacity
- sklearn

You will also need to have an OpenAI API key to use the embedding and GPT model.


## Results

Clusters

<img width="618" alt="image" src="https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/7a01851b-3e73-4ee0-8a06-c7699c9f4ed7">

Summary of Negative Reivews

<img width="608" alt="image" src="https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/ecacf4a7-76a3-4437-b67e-7034454eda78">


