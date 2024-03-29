# Video Game Golden Age Analysis
This project analyzes critic and user review scores along with [sales data](https://www.kaggle.com/datasets/holmjason2/videogamedata) for the top 400 video games released between 1977-2020 to determine if there was a "golden age" based on ratings and sales.
Overview
This project analyzes critic and user review scores along with sales data for the top 400 video games released between 1977-2020 to determine if there was a "golden age" based on ratings and sales.

![photo of video game controller](pexels-pixabay-275033.jpg)
>Photo by Pixabay: https://www.pexels.com/photo/white-gaming-console-on-wooden-surface-275033/

## **Datasets**

### The analysis uses two datasets:

 ### game_sales

| column     | type    | meaning                          |
|------------|---------|----------------------------------|
| game       | varchar | Name of the video game           |
| platform   | varchar | Gaming platform                  |
| publisher  | varchar | Game publisher                   |
| developer  | varchar | Game developer                   |
| games_sold | float   | Number of copies sold (millions) |
| year       | int     | Release year                     |

‎‏‏‎ ‎
 ### reviews

| column      | type    | meaning                          |
|-------------|---------|----------------------------------|
| game        | varchar | Name of the video game           |
| critic_score| float   | Critic score according to Metacritic |
| user_score  | float   | User score according to Metacritic  |



## **Analysis**

#### The Jupyter Notebook walks through the key analysis steps:
+ Joining the game sales and reviewing datasets
+ Calculating average critic and user scores by year
+ Identifying peak years based on the highest average scores
+ Comparing critic vs user top-scored years
+ Finding peak sales years and comparing them to top-scored years
  

## **Insights**

+ The years with the **highest average critic** and **user scores**
+ The **difference between critic** and **user-preferred years**
+ **Peak sales years** and **how they align with top-rated years**
  

## **Contents**
#### The repository contains:

+ Jupyter Notebook with data preparation, analysis, and visualizations
+ CSV files of the cleaned datasets

The notebook has full details on the analysis process and results.
