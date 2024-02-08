---
title: "Prediction in the social sciences"
description: |
  How a focus on prediction can lead to better understanding. 
categories:
  - Overview
  - Prediction
  - Machine learning
  - Data science
author: "Gert Stulp"
date: "2023-06-26"
toc: true
image: ../../images/prediction.png
image-alt: Image downloaded from https://rossum.ai/blog/top-5-predictions-for-ai-in-2022/
language: 
    section-title-footnotes: References
---


The social sciences, understandably, focus on explaining and understanding phenomena. In traditional statistical models, "understanding" is typically achieved in the following way: A relatively small theoretical model is constructed (say, 5 variables), and associations between these variables are specified (typically drawn as arrows in the model). Hypotheses often concern the strength of a particular arrow, which mostly comes down to whether this strength is different from zero (i.e., does X have an effect on Y given Z) in a sample, which in turn is mostly assessed through p-values. This approach has led and will lead to a sophisticated body of research, but it is not without problems. Whether an effect is non-zero or not is not particularly interesting; the p-value does not inform on whether an effect is important, and it is easy to 'manipulate' a p-value towards being below a magic threshold; good "in-sample models" may fail to predict unseen cases well. All of this means that even if we have a highly significant, non-zero effect, this does not necessarily mean we have good understanding. 

This is why recent research has argued that explanatory modelling should be complemented by predictive modelling. That is, there is great benefit to focus on how well a model predicts cases that the model has not seen before. This prediction may be done through machine learning, but this is not the key point for me.  

I hope that my (future) research will help in making this case clearly and convince social scientists of the advantages taking out-of-sample prediction seriously and also how optimising this quantity can lead to increased understanding of the system. 

## PreFer
One of the main ways in which I hope to do this, is the Predicting Fertility data challenge [PreFer](https://preferdatachallenge.nl):

![](../../images/PreFer_logo_LONG.png)

## Related content

This is one of the studies where I use a data-driven approach to a sociological topic: 

Stulp, G., Top, L., Xu, X., & Sivak, E. (2023). A data-driven approach shows that individuals’ characteristics are more important than their networks in predicting fertility preferences. Royal Society Open Science 10(12), 230988. [https://doi.org/10.1098/rsos.230988](https://doi.org/10.1098/rsos.230988)
