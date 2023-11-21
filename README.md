# Advanced Regression - Surprise Housing
> Surprise Housing, a US-based housing company, is expanding its operations to the Australian market. The company utilizes data analytics to make informed decisions about purchasing and flipping houses. The goal is to buy properties below their actual values and sell them at a higher price. This repository contains the code and analysis for building a regression model using regularization to predict the actual value of prospective properties. The model's insights will assist the company in making investment decisions in the Australian real estate market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Surprise Housing, a US-based housing company, is venturing into the Australian real estate market. This project involves the development of a regression model using regularization techniques to predict the actual value of prospective properties. The primary objective is to assist Surprise Housing in making informed investment decisions by understanding how various independent variables influence house prices in the Australian market.
- ### Background of the project
    The background of the project lies in the expansion efforts of Surprise Housing, a US-based housing company, into the Australian real estate market. Recognizing the         potential for profitable investments, Surprise Housing aims to leverage data analytics to make well-informed decisions about purchasing and selling houses in Australia.     The company's strategy revolves around acquiring properties at prices below their actual values and subsequently selling them at higher prices.

    To implement this strategy effectively, Surprise Housing has collected a dataset containing information on the sale of houses in Australia. The objective is to build a      regression model using regularization techniques. This model will serve as a predictive tool, offering insights into the actual values of prospective properties. The        key questions the company wants to address include identifying significant predictors affecting house prices, understanding the role of these predictors in pricing          dynamics, and determining the optimal regularization parameters for ridge and lasso regression.

    The overarching business goal is to model house prices based on available independent variables. By doing so, Surprise Housing aims to gain a deeper understanding of        how prices vary with different factors. This understanding will guide the company's strategic decisions, allowing it to focus on areas that promise high returns, adapt      its approach to the nuances of the Australian market, and establish a solid foundation for success in this new venture. The regression model, once developed, will be a      valuable asset for Surprise Housing in navigating the complexities of the Australian real estate landscape and making data-driven investment decisions.
- ### Business goals
  * Identify Significant Predictors:
        Determine which variables play a significant role in predicting the price of a house in the Australian market.
  * Model Interpretation:
        Understand how well the identified variables describe the price of a house.
  * Optimal Regularization Parameter:
        Determine the optimal value of lambda for ridge and lasso regression to fine-tune the model's performance.
- Dataset - [train.csv](https://github.com/vikaaas-99/Advanced-Regression-Assignment/files/13426344/train.csv)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Conclusions
-  Lasso regression helps in feature reduction (as the coefficient value of one of the lasso's features to be shrunk toward 0) and helps to increase model interpretation by taking the magnitude of the coefficients, thus Lasso regression has a better edge over Ridge regression.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by [@vikaaas-99] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
