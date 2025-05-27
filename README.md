# Cattle mortality in Northern Ireland

_Survival analysis & machine learning_

by Maria (Marietta) Dalamanga, MSc thesis, School of Mathematics and Physics, Queen's University Belfast

## Summary

In this report we present the results of a large scale survival analysis of cattle mortality from across Northern Ireland exploring several risk factors including the sex, geographic area, production type, place of death, and health status. To this end, we used several parametric, nonparametric, and semiparametric methods: Kaplan-Meier estimators, the accelerated failure time and Cox methods, fitting parametric distributions—including mixture distributions—survival forests, and methods from ma- chine learning such as random forests, extreme boosted trees and regression trees. We applied these methods to different subpopulations of the dataset. Best results were obtained using a Cox model with shared frailty term on the herd ID (C- index: 73.52%), and a survival forest on the dairy subpopulation (75.11%). We were also able to predict the life span of male animals using a random forest (RMSE 153.4 days, R2 = 0.65). The sex and certain abattoirs proved to be the main risk factors for cattle survival.



