# Comic Sales

This directory contains my analysis of Marvel comic book sales available from [Comichron](http://www.comichron.com/monthlycomicssales.html) in order to determine the criteria that causes a title to be cancelled. The first two parts walk through each step of the analysis whereas the last part summarizes the key points and presents conclusions.

[Part 1](https://github.com/christopherpease/ComicSales/blob/master/1%20Comic%20Book%20Cancellations%20-%20Web%20Scrapping.ipynb) scrapes sales information from the website, cleans it up, and saves it in a SQL database.

[Part 2](https://github.com/christopherpease/ComicSales/blob/master/2%20Comic%20Book%20Cancellations%20-%20Machine%20Learning.ipynb) trains a variety of machine learning classifiers (DT, RF, KNN, SVM, QDA) on that data to determine the cancellation criteria.

[Part 3](https://christopherpease.github.io/ComicSales/) summarizes the entire process and draws conclusions from my findings.
