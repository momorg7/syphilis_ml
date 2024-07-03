# Evaluating undersampling techniques in the prediction of potential congenital syphilis cases using real data from Pernambuco, Brazil

Codes related to my masters thesis about congenital syphilis and undersampling.

The paper that resulted from my thesis is currently under review by the journal International Journal of Data Science and Analytics and can be acessed as a preprint at https://www.researchsquare.com/article/rs-4524217/v1. 

Also, this work earned me a best work prize in the master category at the event MOSTRA POLI 2023 from Universidade de Pernambuco.

Abstract:

Syphilis can be transmitted congenitally and may cause serious consequences for the child if not treated. The Programa Mãe Coruja Pernambucana (PMCP) is a brazilian public health program that helps pregnant women and saves data that can be used for prediction of potential congenital syphilis cases, through machine learning models. Only one work was found that predicts congenital syphilis through machine learning. This research uses a different methodology that evaluates undersampling in prediction. Random Undersampling, UnderSampling Based on Clustering (SBC) and NearMiss were used. The data was preprocessed and undersampling applied, generating different balanced datasets to train and test different machine learning models and different metrics for evaluation. Undersampling discarded data evaluation and analysis of distribution of the best attributes were applied to evaluate undersampling in best models. In models results, NearMiss trained models had high metrics, and very low in the discarded data. SBC models had smaller metrics, and in the discarded data went lower. Random Undersampling models had the lowest metrics, however in the discarded data showed similar results. The distribution of best attributes of NearMiss models were not similar to the original, contrary to Random Undersampling and SBC. NearMiss models had best results in the models, through this work evaluation showed that they cannot generalize the PMCP data and have not a representative distribution of the original data. Random Undersampling models had the lowest metrics but showed consistency through the evaluations, and thus are recommended for the congenital syphilis prediction.
