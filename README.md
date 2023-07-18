# Google Maps App Review Analysis

## Objective

The main objective of this project is to analyze the reviews of the Google Maps app and identify common negative comments. These insights can be used to understand user pain points and inform product enhancements.


## Steps

1. **Data Retrieval**: The data used is loaded from a CSV file which contains Google Maps app reviews.

2. **Data Processing**: The reviews data is cleaned and formatted for further analysis.

3. **Embedding with GPT Model**: The reviews are embedded using a service provided from OpenAI. This step converts the reviews into a form that can be used for further analysis.

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


## Overview of data

![image](https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/dafad152-c606-4aaa-a310-ff4e3b3beb5f)


![image](https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/b683e682-4d3b-43c3-bc25-eb322098a2a5)


**Clusters**
<p align="center">
<img width="800" alt="image" src="https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/7a01851b-3e73-4ee0-8a06-c7699c9f4ed7">
</p>



## Results

### Summary of Negative Reivews

<p align="center">
<img width="800" alt="image" src="https://github.com/dlworudgg/googl_maps_app_review_analysis/assets/37742961/ecacf4a7-76a3-4437-b67e-7034454eda78">
</p>


### Review summary related to Saved-place

1. Users want the "I haven't been there" option back when asked for reviews.
2. Some users lost all their saved places after an update.
3. Users find it hard to pull up saved places due to lack of search or sorting options.
4. Users report issues with saved places showing as coordinates instead of names.
5. Users report issues with downloading saved places.
6. Users report issues with saved locations not coming up in the search bar.
7. Users can't set more than one workplace or create shortcuts to other saved places.
8. Users are frustrated with the handling of saved places, which often don't show up on the map.
9. Users are upset about the disappearance of saved locations and the inability to view all saved places on the "explore" page.
10. Users are upset about the app's inability to continuously share location with people they've allowed to see.
11. Users are frustrated with the app's inability to use different icons for different saved places lists.
12. Users are frustrated with the app's inability to save places in lists or view the list of marked places.


### Review summary related to reviews

1. Some users have expressed frustration over the inability to post negative reviews or have their negative reviews removed.
2. A few users have expressed dissatisfaction with the review system, claiming that it favors businesses over users.
3. Some users have reported that their reviews have been deleted without their consent.

