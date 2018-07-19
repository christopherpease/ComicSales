# Comic Sales

This directory contains my analysis of comic book sales available from [Comichron](http://www.comichron.com/monthlycomicssales.html) in order to determine the criteria that causes a title to be cancelled.

[Part 1](https://github.com/christopherpease/ComicSales/blob/50b0ce84eb0b37a285bc578e564eeaf09a90dd6c/1%20Comic%20Book%20Cancellations%20-%20Web%20Scrapping.ipynb) scrapes sales information from the website, cleans it up, and saves it in a SQL database.

[Part 2](./1 Comic Book Cancellations - Web Scrapping.ipynb) trains a variety of machine learning classifiers (DT, RF, KNN, SVM, QDA) on that data to determine the cancellation criteria.
