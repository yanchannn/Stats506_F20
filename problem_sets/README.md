## Problem Sets

This directory is used to provide supporting material and solutions for
Stats 506 (F20) problem sets. These are described briefly below.

## Templates

The [templates](./templates) directory contains script templates for
the various languages used in the course.  Currently, this contains:

 1. `psX_template.sh` -	A shell scripting template.
 1. `psX_template.R` - a template for R scripts
 1. `psX_template.Rmd` - a template for Rmd files
 1. `psX_spin_template.R` - the Rmd template converted for use with
     `kintr::spin()`.

## Data

 1. [isolet_results](./data/isolet_results.csv) contains true values
    `y` (1 = vowel, 0 = consonant) and predicted probabilites `yhat`
    on the test set (`isolet5.data`)
    for the [isolet data](https://archive.ics.uci.edu/ml/machine-learning-databases/isolet/).
    The predictions are taken from a logistic model fit using ridge
    regression to the training data (`isolet+1+2+3+4.data`). 
