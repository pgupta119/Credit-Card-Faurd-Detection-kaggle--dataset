# Credit-Card-Faurd-Detection-kaggle--dataset


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#About-the-project">About The Project</a>
      <ul>
        <li><a href="#Context">Context</a></li>
        <li><a href="#Content">Context</a></li>
        <li><a href="#Inspiration">Context</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#Pre-requisites">Pre-requisites</a></li>
        <!--<li><a href="#installation">Installation</a></li>-->
      </ul>
    </li>
    <li><a href="#Packages">Packages</a></li>
    <!--<li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
<li><a href="#acknowledgements">Acknowledgements</a></li>-->
  </ol>
</details>

## Context

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


##Inspiration
Identify fraudulent credit card transactions.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification



## Getting started

### Pre-requisities

To clone and run this application, you'll need [Git](https://git-scm.com) and  [Jupyter notebook](https://test-jupyter.readthedocs.io/en/latest/install.html) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone git@github.com:pgupta119/Credit-Card-Faurd-Detection-kaggle--dataset.git

# Go into the repository
$ cd Credit-Card-Faurd-Detection-kaggle--dataset

# run Fraud Credit Card.ipynb file
```

##  Packages
* [numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

