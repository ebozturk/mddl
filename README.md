#  Project 'mddl'
The repo provides the source R codes of 'The Effect of Missing Data Mechanisms on Deep Learning Algorithm Binary Classification' manuscript

# Overview of the study

Investigating the effects of the missing data and the methods to overcome problems in statistical models caused by missingness is a significant research topic due to the complex nature of the data include missing observations. The different approaches in case of the missing data are complete case analysis and missing data imputation. Besides, to handle missing data issues, one needs to search missing data mechanisms and patterns. However, understanding the missing mechanism is not easy in relatively large data sets. Recently, deep learning algorithms have been widely used for classification, regression or clustering tasks in large data sets due to the computational advances. The objective of this study is to present the effect of missing data on the performance of the binary classification problem considering the missing proportion, the correlation structure and the mechanism of the missing in the dataset. To achieve the aim of this study, an extensive simulation study is conducted using Virtual Machine on Microsoft Azure. In the following figure, it is seen that both the proportion of the missing and correlation level between features affect the performance of the deep learning classification algorithm in different missing mechanism including MCAR, MAR and MNAR for test datasets. However, there is slightly higher AUC values with smaller deviations obtained in all missing mechanisms when incomplete datasets were used without imputation. This indicates that deep learning algorithms can overcome the problem caused by missingness. 

![text](https://github.com/ebozturk/mddl/blob/main/descriptive_statistics/test_dataset_results_boxplot.jpeg)

# References

1. Demirtas, H.,  Amatya,  A.,  Doganay,  B.:  Binnor:  An  R package for concurrent generation of binary and normal data. Communications in Statistics-Simulation and Computation 43(3), 569–579 (2014).
2. LeDell, E., Gill, N., Aiello, S., Fu, A., Candel, A., Click,C.,  Kraljevic,  T.,  Nykodym,  T.,  Aboyoun,  P.,  Kurka,M., Malohlava, M.: h2o: R Interface for the “H2O” Scalable  Machine  Learning  Platform  (2020).   URL https://github.com/h2oai/h2o-3.  R package version 3.30.0.7
3. Honaker, J., King, G., Blackwell, M.: Amelia ii: A program for missing data.   Journal of Statistical Software, Articles 45(7), 1–47 (2011). 
4. van Buuren, S., Groothuis-Oudshoorn, K.: mice: Multi-variate imputation by chained equations in r.  Journal of Statistical Software, Articles45(3), 1–67 (2011). 
5. Wickham, H.: ggplot2: Elegant Graphics for Data Analysis.   Springer-Verlag New York  (2016).   URL https://ggplot2.tidyverse.org27.  

**For further questions: ebru.ozturk3@hacettepe.edu.tr**
