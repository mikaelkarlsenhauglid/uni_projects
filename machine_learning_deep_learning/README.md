# UFC-Fight-Prediction

This project uses historical UFC data—including fighter statistics, biological data, and bookmaker odds—to predict the outcome of UFC fights using machine learning. The goal is to evaluate whether ML models can outperform betting sites in predicting winners.
We explore various data preprocessing techniques and feature selection methods to identify the most influential factors in fight outcomes. Multiple ML models are trained and tested, and the best-performing models are deployed in a simulated betting strategy to assess real-world applicability.

**Research Question**
Can machine learning be used to predict UFC fight winners better than bookmakers?

**Keywords:** UFC, machine learning, odds, sports betting, binary classification, logistic regression, random forest, XGBoost, multi-layer perceptron

**Abstract:** This paper investigates whether machine learning models can predict the outcomes of Ultimate Fighting
Championship (UFC) fights better than bookmakers. Based on the Ultimate UFC Dataset, we construct four
distinct datasets using data preparation strategies such as feature extraction and feature selection. We also test the
effects of including the odds as a feature in one of the datasets. We evaluate logistic regression, random forest,
XGBoost, and multilayer perceptron (MLP) models, optimizing each based on AUC-ROC performance. While
models trained with odds achieved higher predictive accuracy, up to 71% with an AUC of 0.7599, their
performance in a simulated betting strategy was often inferior to models trained without odds, due to high
correlation with the bookmakers’ predictions. The results indicated that both the MLP and logistic regression
models performed better than XGBoost and random forest. Our findings show that although ML models can
marginally outperform bookmakers in predictive metrics, their true value lies in spotting overlooked winners,
highlighting the importance of combining performance metrics with deployment-based evaluation. This study
contributes to the growing body of research on sports prediction by demonstrating that, under specific
conditions, ML can provide a competitive edge over bookmakers in UFC outcome forecasting.
