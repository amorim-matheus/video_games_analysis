# Video Games Analysis
## Table of Contents
1. [Project Motivation](#motivation)
2. [Installation](#install)
3. [Files Descriptions](#files)
4. [Summary of Results](#summ)
5. [Licensing, Authors, and Acknowledgements](#licensing)
## Motivation of the project <a name="motivation"></a>

I am a huge fan of video games since I was a boy, and more recently I got quite fond of working with data, so I thought this was a great opportunity to join both worlds!
Looking at the data, I aim to create recommendations for different people looking for different kind of both video games and platforms. Mind you that this will not be a machine learning model, mainly because I don't think I have enough data/variables to run a model, nor the preference of each cluster of customer.
Based solely on sales, I will answer the following questions:

1. What are the most popular games per genre? In case someone is looking to buy a sports game (for example), which one should I recommend for this person?
2. Are there any platforms that are preferred for any genre of games? So let's say someone really enjoys shooting games, which console should I recommend for this person?
3. For each generation of video games, which platform had most games sold, and which video games were sold the most? In case someone is looking for video games recommendation for, let's say, his or hers Super Nintendo, which ones are the blockbusters, that I should recommend they have?

To answer these questions, I used data from [this dataset](https://www.kaggle.com/gregorut/videogamesales) published on Kaggle, and the below libraries.

## Installation <a name="install"></a>

In addition to the standard distribution of Python 3.x, you will need to install the following libraries (won't specify any version because the code should run fine in whatever version of the following libraries):

1. Pandas
2. Numpy
3. Matplotlib
4. Seaborn
5. Plotly
6. Jupyter Notebook

All of these libraries with exception to Plotly already come with the standard Anaconda distribution.
You can use the file `requirements.txt` to install all these. You just need to download the file and run the command:
>python -m pip install requirements.txt.

## Files Descriptions <a name="files"></a>
<b><ins>Video Game Sales Analysis Jupyter Notebook:</ins></b> All of the analysis is conducted inside this file, running Python on a Jupyter Notebook platform. The notebook is fairly commented and contains markdown from start to finish to be more easily understood.

<b><ins>vgsales.csv:</ins></b> This file contains the raw data extracted from Kaggle, in case you want to explore it more on your own.

## Results <a name="summ">
The findings of the analysis can be found in the post available [here]().

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must first give credit to GregorUT GitHub user, who developed the scrapper that gathered the data used in this analysis (repository saved in [this link](https://github.com/GregorUT/vgchartzScrape), in case you are curious). Besides, also acknowledge Stack Overflow for the invaluabule source data and Kaggle for being an amazing source of datasets and analysis.

Distributed under the MIT License. See `LICENSE` for more information.
