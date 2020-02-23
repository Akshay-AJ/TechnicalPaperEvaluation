# Data Munging and Predictive Analysis for ICC Cricket World Cup 2019

Predicting the winner of 2019 cricket world cup using random forest algorithm


I used Machine Learning to make a model using scikit-learn, pandas, numpy, seaborn and matplotlib to predict the results of ICC 2019 Cricket World Cup.


# Goals
I used data sets from Kaggle - Results of the matches since 1975 and 2017. I didn't get the data for 2018 and 2019 so this model might not be that accurate but still I believe this gives a fairly good intuition. Also I removed all the data from 1975 to 2010 since what happened way back in the past will have much less weight than the recent results. For the rest of data files I used the crickbuzz website.

# Environment and tools
1. Jupyter Notebook
2. Numpy
3. Pandas
4. Seaborn
5. Matplotlib
6. Scikit-learn

I used the ICC ranking as of MAY 2019 dataset and a dataset containing the fixture of the group stages of the tournament. I compared Support Vector Machines, Logistic Regression, Random Forest and K-Nearest Neighbours model.

I had also discussed the basic "Time Series Analysis" prediction methodology along with Holt's Winter Exponential Smoothing methods in Python.

Random Forest was the winner with a training accuracy of 70 % and test accuracy of 67.5%.

# Installation
pip install -r requirements.txt

jupyter notebook

-> According to this model England is likely to win the Cricket World Cup.

# Areas of further Improvement
1. Dataset - to improve dataset you could use 2018 and 2019 years into account by scraping them from the ESPN website and also possibly use the players data to assess the quality of each team player.

2. A confusion matrix would be great to analyse which games the model got wrong.

3. We could ensemble that is we could try stacking more models together to improve the accuracy

# References
https://arxiv.org/abs/1806.03208



