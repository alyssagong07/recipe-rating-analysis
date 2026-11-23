# What Makes a Recipe Highly Rated?

**DSC 80 Project 4 — UC San Diego**

## Introduction

What makes a recipe highly rated? This project explores how recipe characteristics, such as preparation time, number of ingredients, and number of steps, relate to user ratings.

Using the Recipes and Ratings dataset, I investigate patterns in recipe ratings through exploratory data analysis, hypothesis testing, and predictive modeling.

## Data Cleaning and Exploratory Data Analysis

The project uses two datasets from Food.com: a recipes dataset containing recipe characteristics and an interactions dataset containing user ratings. These datasets were merged using recipe IDs to connect each recipe with its average user rating.

The cleaned dataset contains **83,782 recipes**, including **81,173 recipes with recorded average ratings** and **2,609 recipes without ratings**.

The analysis focuses on preparation time (`minutes`), number of ingredients (`n_ingredients`), number of steps (`n_steps`), and average recipe rating (`rating`). These variables help investigate whether recipe complexity is associated with user ratings.

### Exploratory Data Analysis

I explored the relationships between recipe characteristics and average user ratings, focusing on preparation time, number of ingredients, and number of steps.

The analysis investigates whether recipes that require more time, ingredients, or steps tend to receive higher or lower ratings. These comparisons help identify potential patterns and provide context for the hypothesis tests and predictive models developed later in the project.

### Distribution of Average Recipe Ratings

<iframe src="rating_distribution.html" width="100%" height="500" style="border:none;"></iframe>

**Interpretation:** The distribution of average recipe ratings shows how ratings are spread across recipes. By examining the frequency of different ratings, we can understand the overall rating patterns in the dataset and establish context for investigating which recipe characteristics are associated with higher ratings.

### Distribution of Recipe Preparation Times

<iframe src="preparation_time_distribution.html" width="100%" height="500" style="border:none;"></iframe>

**Interpretation:** The distribution of recipe preparation times is right-skewed, meaning most recipes take relatively little time to prepare, while fewer recipes require longer preparation times. This visualization focuses on recipes taking between 1 and 180 minutes to make the distribution easier to interpret.
