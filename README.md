# Diet Classification

## Introduction
Veganism was first coined in 1944, by Dorothy Morgon and Donald Watson. Veganism in essense is a lifestyle built on the idea of consumption. It is the abstinence of consumption of meat, eggs, cheese, honey i.e. any produce by animals. This also applies to the consumption of by-products of clothing , or accessory (i.e. leather goods, ivory, pearls) made from animals. [(Time, 2008)](https://time.com/3958070/history-of-veganism/)

Veganism interest has made its way into the all time high in the recent years. This popularity is further boosted as the global climate change has changed perspective and its deeper meaning as part of the driver to reduce the use of finite resources sparingly. [(National Geographic, 2014).](https://www.nationalgeographic.com/culture/article/vegetarianism-more-than-meats-the-eye)


## Problem Statement
As more and more vegan products are hitting the market in these recent years, we seek to find the idiosyncrasy of temporal-fad diet versus purposeful-lifestyle diet in the perspective of consumers. 

With this findings, we are able to learn the driving popularity amongst modern dietary and the ingredients that is suitable for their choice of diet which are vegan-friendly product as well. This will help to redirect the resources in research and development of products for customer acqusition. 

Using classification model with logistic regression and naive bayes, we want to investigate ingredients that associates and/or differentiate the vegan lifestyle over high fat adequate diets (keto diet). The classification model will be evaluated via accuracy score and verified by domain knowledge of the diet of choice

## Executive Summary  

With veganism on the rise and competing with other fad-diets, it has come to light that we could take this opportunity to specialise in products that will offer a win-win situation. 

>What if we could market products suitable for both dietary community?

Using NLTK, TfidfVectoriser and logistic regression model, we are able to identify the top important words in the conversation among the community and dive deep into the list of ingredients that is being discussed. This shines light to what is the common acceptable ingredients used and the rest would be up to the marketing team to identify its feasiblity of production.

In the exploratory data analysis, we also find that dieters struggle with overwhelming information on what can or cannot be consumed. As solution provider, we want to make it fool-proof and easy for consumers to make decision. Knowing the keywords that dieters use, would make it easy for naming and packaging of products as well, killing two birds with one stone. 

The classification model will help to identify and pinpoint the company next R&D product in the right direction. Instead of trying to cast an entire net across the market, we can focus the resources to develop food products that will interest certain dietary group.

## Technical Findings

Using Tfidf and Logistic Regression, we find the **accuracy** of the model at 0.95 with **sensitivity** at 0.98 and **specificity** at 0.93. Overall false positive and false negative counts were low and adjustment on the threshold is not required as we are interested in the top keywords of respective reddits. 

![Confusion Matrix](/images/Confusion_Matrix.png)

Top keywords by coeficient of logistic regression model shows below

![Word Importance](/images/Word_Importance.png)