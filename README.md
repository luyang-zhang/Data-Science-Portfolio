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


## 3. Prediction Models for NBA Players’ Performance (Neural Networks, Random Forests)

Summary:
In this project, we tackled the challenging task of accurately predicting the future performance of NBA players. The accuracy of such predictions is pivotal for a team's success and financial stability. Leveraging clustering and machine learning techniques, we aimed to enhance the understanding of predicting NBA players' success based on their early career statistics.

Approach:
We employed a Gaussian mixture model to cluster and label guards and forwards into top, middle, and bottom tier players. The clustering process encompassed player statistics from their fourth season until retirement. To predict a player's tier, we utilized neural networks and random forest classifiers, focusing on statistics from their first three seasons.

Key Findings:
Through rigorous experimentation, the random forest classifier demonstrated superior performance over the neural network model. This success is attributed to its heightened ability to predict elite and lower-tier players. Furthermore, our project affirmed the significance of conventional predictors, including points and minutes per game, while also unearthing other insightful predictors for evaluating young guards and forwards.

Impact:
This project not only showcases our data science skills but also highlights our ability to tackle complex real-world challenges. By providing valuable insights into the predictability of NBA player performance, this work underscores the potential of data-driven strategies in enhancing team dynamics, success, and financial decisions.

[View Report Here](https://github.com/luyang-zhang/Data-Science-Portfolio/blob/ba952775c700f2812b2ac5c8a03be0bb2fcf1edd/STA%20221%20Final%20Project%20Report.pdf)


## 4. Binary Classification Analysis of Customer Subscriptions (Bayesian Additive Regression Trees, Support Vector Machine, Logistic Regression)

__Summary__:
In this project, we harnessed the growing potential of machine learning in driving business success. We created a binary classification model capable of accurately predicting whether customers would subscribe to a bank’s term deposit product post-marketing calls. Our primary focus shifted to the Bayesian regression additive tree (BART) model among four candidates, including logistic regression, support vector machine, and random forest.

Approach:
We explored the merits of BART for this prediction task, delving into its underlying theory and concepts. Our study demonstrated how BART effectively unearthed crucial features beneficial for marketers' campaigns. The BART model achieved impressive results, boasting an area under the curve of 0.802 (95% CI 0.779 − 0.814) and a high accuracy rate of 90.010%.

Insights:
We unveiled the role of social and economic factors in influencing individuals' decisions to subscribe to long-term deposits, adding a valuable layer of understanding to marketing strategies.

Future Directions:
While our project yielded promising outcomes, we acknowledged the model's limitations. Additionally, we contemplated potential enhancements for leveraging machine learning in the dynamic realm of marketing.

Impact:
By successfully implementing a robust predictive model and providing insights into customer behavior, this project showcases our proficiency in utilizing machine learning to address critical business challenges.

[View Report Here](https://github.com/luyang-zhang/Data-Science-Portfolio/blob/bc63fb3b6345d1be691401dd897a8eec53295e8e/Group_5_STA_208_Project.pdf)
