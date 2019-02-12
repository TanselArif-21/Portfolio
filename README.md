# Portfolio
My portfolio of projects and articles

## Published Articles
1. **Gambler's Ruin** (Keywords: Probability, Statistics, Pygame, Random Walk)

Published at locations: https://www.datasciencecentral.com/profiles/blogs/gambler-s-ruin-simulations

This article goes through theory to the Gambler's Ruin problem and creates visually progressing simulations using Pygame so that the user can see the progression of the simulations towards the theoretical values.

The problem is summarised as follows: A Gambler begins with $k. At each gamble, the Gambler either wins $1 with probability p or loses with probability 1-p. Assume that the Gambler will stop gambling if the Gambler's fortune reaches $N or $0. Find the probability that the Gambler goes bankrupt.

An app is also created for simulation purposes displaying the trajectory in typical Random Walk style allowing the user to specify the probability p, the initial fortune k and the maximum value N etc... The app will also display these parameters as well as the probability obtained via the theory.

The accompanying pdf contains more indepth details as well as demonstration and theory derivation.

## Statistical Learning
1. **Linear Regression**

This project introduces the theory behind linear regression, metrics such as r-squared, and the calculation of p-values and F-Statistics. For each of the concepts that are commonly applied through packages, it is shown how the behaviour/results from these packages compare to manual application of these concepts. It is shown how variable selection can be applied using the r-squared statistic iteratively. Finally, Cross Validation is applied, both manually as well as part of popular packages.

2. **Logistic Regression**

This project introduces the theory behind logistic regression, such as the calculation of p-values and F-Statistics. For each of the concepts that are commonly applied through packages, it is shown how the behaviour/results from these packages compare to manual application of these concepts.

3. **Bayesian Inference**

An application hypothesis testing using both Bayesian Inference with a Jeffreys Prior and usual T-Tests. Showing that these two approaches agree with each other as is the intention of such a prior.

4. **ML Applications**

Some applications of Machine Learning from various sources:
  - **Titanic** (Kaggle)
  - **Housing** (Kaggle)
  
5. **ML App**

A simple web app is created demonstrating the following functionality:
  - Allow the user to upload data and make a prediction of the price of a house. This pertains to a house prices dataset obtained from Kaggle.  The distribution of the data as well as the prediction is shown to the user. Currently, the app uses only LinearRegression on multiple predictors. However, more sophisticated models can be slotted in.
  - Allow the user to upload review information in the form of text and perform Latent Discriminant Analysis (along with tf-idf) to obtain a word cloud highlighting the most important terms. Topics are also produced but these aren't displayed to the user. The input data to the app is created using the **Web Scraper** app in this portfolio.

The app uses Python/Flask and is only a template and so is built to run on a local server.

## Utilities
1. **CustomURIParser**

The application of proper source control as well as unit tests in order to create a URI parser with the ability to determine if a string is a valid URI, whether it be relative or absolute.

2. **Web Scraper**

This script allows the user to read review information from the review sites Tripadvisor and Yelp. It contains 1 second wait time between requests in order to conform with fair use and detect import errors due to unstable internet connection and attempts to re-import. A similar procedure can be employed to gather information from other sites that do not have APIs.
