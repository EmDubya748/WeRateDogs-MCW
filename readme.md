## Purpose

The purpose of this project is to perform basic data wrangling of the WeRateDogs twitter account, using a pre-existing set of tweets from the Udacity classroom. This repository contains the project that I passed towards the end of the Udacity Data Analyst program, in which we performed basic Data Wrangling activities.

## Questions

The main guiding question we tried to look at was "who is the goodest dog" amongst the tweets.

## Methods

Basic data visualization

## Getting Started

1. Clone this repository ([Instructions](https://help.github.com/en/articles/cloning-a-repository) for cloning).

2. Input Twitter API credentials into the Jupyter notebook. A guide on generating access keys can be found [here](https://developer.twitter.com/en/docs/basics/authentication/guides/access-tokens.html). You will need a Twitter developer account to generate these keys.

3. A list of the tweets of interest is uploaded with this repository for convenience (twitter-archive-enhanced.csv). Another list of tweets associated with an image predictor algorithm is also uploaded (twitter_archive_master.csv). Since both files contain fewer than 3000 rows each, I decided to upload them for convenience.

4. Package requirements can be found in the requirements.txt file.

5. Run the Jupyter Notebook. Note that this should take between 10 - 20 minutes to run, because Twitter limits the amount of Tweet data we can pull. Therefore, we have functionality to pull Tweet data in batches.

## Limitations

This project was focused primarily on Data Wrangling. While we came up with many issues to fix, there are still probably some more lurking around. We did some Exploratory Data Analysis (EDA), but nothing too crazy.

## Credits

* Example readme file template 1: https://github.com/sfbrigade/data-science-wg/blob/master/dswg_project_resources/Project-README-template.md

* WeRateDogs twitter account: https://twitter.com/dog_rates

* Udacity Data Analyst Program contents
