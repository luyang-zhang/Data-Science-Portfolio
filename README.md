# Data Science Portfolio
### Luyang Zhang
[Linkedin](linkedin.com/in/luyzh) 
## 1. Multiple Linear Regression Study for Beta-Carotene Level in Human Body 

- Constructed a multiple linear regression model of beta-carotene
- Conducted exploratory data analysis of univariate and multivariate data, including pie charts, histograms, and boxplots
- Using stepwise model selection to get a reduced model, improved model explanatory power by 3% from the full MLR model 
- performed ANOVA and diagnosed models including hypothesis testing and cross validation
- Pinpointed the top five strongest predictors of beta-carotene levels

The relationship between beta-carotene levels and several different predictors were analyzed, based on data from 315 patients from an observational study. Body mass index and calorie intake were negatively related to beta-carotene levels. Fiber intake and the consumption of vitamins were positively related to beta-carotene levels. Furthermore, there was a statistically significant interaction between smoking and dietary carotene in determining beta-carotene levels. These results confirm the importance of predictors identified in prior literature, but also propose additional determinants of beta-carotene levels.

[View Report Here](https://github.com/luyang-zhang/Data-Science-Portfolio/blob/6786f7f8470c3a1a294646ae3020b0c2561f1ce1/1.%20Multiple%20Linear%20Regression.pdf)

## 2. Examining Variation in Neurons’ Visual Encoding Mean Firing Rate
- Implemented a three-way Analysis of Variance (ANOVA) model with mixed effects to make inference of the variation in the response mean firing rate
- Fitted a logistic regression model with a accuracy of 77% for predicting a mouse receive penalty or reward
- Conducted Linear Discriminant Analysis (LDA) for the same task and have similar results.

In an experiment conducted by Nicholas A. Steinmetz et al., the neural activity in the visual cortex was analyzed from 1,196 trials. A three-way mixed effects ANOVA model was used to test the hypothesis that contrast levels and their interaction have an impact on neurons' mean firing rate. The model indicated that the mean firing rate of neurons after visual stimuli presentation is affected by the contrast levels of two visual stimuli and their interaction, while accounting for each experiment session as a random factor.

Model diagnostics and sensitivity analysis were performed, including residual plots, normality tests, and homoskedasticity tests. In the second part of the project, a logistic regression model and linear discriminant analysis were used to predict whether mice receive a reward or penalty. These models achieved 77% accuracy with a true positive rate (TPR) of around 96% and a false positive rate (FPR) of approximately 77%. Finally, an alternative model based on linear discriminant analysis (LDA) was trained, yielding similar results.

[View Report Here](https://github.com/luyang-zhang/Data-Science-Portfolio/blob/4b9d7cf88c919c6bffeb84d0606659278b3b23f9/Examining%20Variation%20in%20Neurons%E2%80%99%20Visual%20Encoding%20Mean%20Firing%20Rate.pdf)


## 3. Prediction Models for NBA Players’ Performance
- Clustered players performance data using a Gaussian mixture model to identify top, middle, and bottom tier players.
- Utilized neural networks and random forests to predict future performance based on early career statistics, achieved a true
positive rate as high as 81%.

This study aimed to enhance the accuracy of predicting NBA player performance by employing clustering and machine learning techniques. Using Gaussian mixture models, guards and forwards were categorized into top, middle, and bottom tiers based on their early career statistics. The analysis extended to clustering players throughout their careers. By employing neural networks and random forest classifiers, the research predicted player tiers using data from their first three seasons. The random forest classifier demonstrated superior performance due to its capacity to accurately classify players as elite or lower tier. Additionally, the study reaffirmed the significance of traditional performance indicators like points and minutes per game, while also introducing new predictors that shed light on evaluating young guards and forwards in novel ways. This research has implications for team success and financial planning in the NBA.

[View Report Here](https://github.com/luyang-zhang/Data-Science-Portfolio/blob/ba952775c700f2812b2ac5c8a03be0bb2fcf1edd/STA%20221%20Final%20Project%20Report.pdf)
