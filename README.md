# Wookieepedia science
#### Data science using Wookieepedia data
#### May the fourth 2021
#### https://linkedin.com/in/dennisbakhuis
Last year I created a [blog post for the Star Wars celebration day](https://towardsdatascience.com/a-neural-network-from-scratch-c09fd2dea45d)
and by making another one this year, it is officially a tradition!

This year I have scraped all canon articles from the Wookieepedia and
applied various data science techniques on the dataset. The results
are pretty funny I say so myself.

[You can find full blog post here.]()

## Notebooks
Analysis is divided in five notebooks:
1. [Scraping wookieepedia]()
2. [Data exploration]()
3. [Wordcloud]()
4. [Topic modeling]()
5. [Network analysis]()

## Python environment
All analysis is performed in Python 3.8. Below is a short
description to create the environment using Miniconda. Are
you new to Python environments? [Here](https://towardsdatascience.com/environments-conda-pip-aaaaah-d2503877884c) is a blog post explaining
my method.
```bash
conda create --name wookiescience python=3.8
conda activate wookiescience
pip install -r requirements.txt
jupyter lab
```
