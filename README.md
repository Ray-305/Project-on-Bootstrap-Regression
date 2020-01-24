# Implementation of Bootstrapping Technique

## Introduction

Bootstrapping is a non-parametric technique that does not require distributional assumptions (such as normally distributed errors),and can provide more accurate inferences when the data are not well behaved or when the sample size is small. Bootstrapping uses the sample data to estimate relevant characteristics of the population.The sampling distribution of a statistic is then constructed empirically by resampling from the sample. The goal of this study is to examine whether a bootstrap regression gives similar parameters (beta estimate and standard errors) as compared to a simple linear regression using the UCLA Graduate Dataset.

We used the open source UCLA Graduate Dataset which was available on Kaggle for this study. For this study, we implemented two steps- 1) Perform a linear regression and a Bootstrap regression on the same dataset 2) Compare the model parameters in the two cases
