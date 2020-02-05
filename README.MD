# Ensemble Classifiers for Imbalanced Dataset

A dataset is imbalanced if the classification categories are not approximately equally represented. 
Data sampling techniques attempt to alleviate the problem of class imbalance by adjusting the class distribution of the training data set. This can be accomplished by either removing examples from the majority class (undersampling) or adding examples to the minority class (oversampling).

In this repository, SMOTEBoost, RB-Boost, and RUS-Boost as three approaches to building ensembles of classifiers for two-class imbalanced data sets have been implemented and their performance measures and ROC curves on 5-fold imbalanced <a href="https://sci2s.ugr.es/keel/dataset.php?cod=999">yeast</a> dataset have been reported and their results have been compared with SVM classifier and AdaBoost-M2 and RandomForest ensembles.


# References:

> <a href="https://dl.acm.org/doi/abs/10.5555/1622407.1622416">[1]</a> Chawla, Nitesh V., et al. "SMOTE: synthetic minority over-sampling technique." Journal of artificial intelligence research 16 (2002): 321-357.

> <a href="https://link.springer.com/content/pdf/10.1007/978-3-540-39804-2_12.pdf">[2]</a> Chawla, Nitesh V., et al. "SMOTEBoost: Improving prediction of the minority class in boosting." European conference on principles of data mining and knowledge discovery. Springer, Berlin, Heidelberg, 2003.

> <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.51.6252&rep=rep1&type=pdf">[3]</a> Freund, Yoav, and Robert E. Schapire. "Experiments with a new boosting algorithm." icml. Vol. 96. 1996.

> <a href="https://www.sciencedirect.com/science/article/pii/S0950705115001720">[4]</a> Díez-Pastor, José F., et al. "Random balance: ensembles of variable priors classifiers for imbalanced data." Knowledge-Based Systems 85 (2015): 96-111.

> <a href="http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.309.2305&rep=rep1&type=pdf">[5]</a> Seiffert, Chris, et al. "RUSBoost: A hybrid approach to alleviating class imbalance." IEEE Transactions on Systems, Man, and Cybernetics-Part A: Systems and Humans 40.1 (2009): 185-197.
