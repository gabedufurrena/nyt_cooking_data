# nyt_cooking_data
This is a brief analysis of the New York Times Cooking's recipe data

## Introduction

This project is meant to answer a single question: What are the top 30 ingredients mentioned in the New York Times Cooking's recipe collection? 
As simple as this question appears to be, the data set used to answer the question requires excessive clean-up, therefore making this project more of an 
exercise in data tidying than anything else.

### The Data

NYT Cooking has published on GitHub their ingredients snapshots from 2015, which is a meticulously parsed csv based on thousands of recipes from their 
collection. The file used for this project is `nyt-ingredients-snapshot-2015.csv`. 

### Analysis

The csv file mentioned above includes a column for every ingredient, how much of the ingredient is used, and how the ingredient is prepared. There is a lot
to unpack here, but for the sake of answering our question, we will be looking exclusively at the `name` column.
