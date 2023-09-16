# PCA.....Only-About-Dimensionality-Reduction??
PCA is a tool that is used to reduce the dimension of the data. It allows us to reduce the dimension of the data without much loss of information. PCA reduces the dimension by finding a few orthogonal linear combinations (principal components) of the original variables with the largest variance.
The first principal component captures most of the variance in the data. The second principal component is orthogonal to the first principal component and captures the remaining variance, which is left of the first principal component, and so on. There are as many principal components as the number of original variables. These principal components are uncorrelated and are ordered in such a way that the first several principal components explain most of the variance of the original data. 
We tried explaining applications of PCA using 4 datasets in the simplest form. Till we did that project the only application we did was DR. But we did some research and found out that PCA is more than just DR.  It has some other very important applications. Dimensionality Reduction is reducing the dimensions of the data which are least correlated. But later we found about obfuscating data, noise reduction, and anomaly detection.
1.	For Dimensionality Reduction we took a dataset consisting of images of famous people. Because the dataset file was heavy, we only took the first 24 images. After that, we applied PCA in such a way that most of the information is contained in a smaller number of attributes. For example, in this dataset, say PCA is applied on each picture in such a way that the images are not clear but still we can identify the person. For example, the picture of George Bush is not clear but you can still identify it’s George Bush in the picture.
2.	Second application is Obfuscating Data. Obfuscating in a literal sense is hiding the data. For this, we used a credit card dataset. This data is highly confidential and that’s where PCA is used to hide the confidential information. When someone asks banks or credit card companies to share their data for a study, they can’t do it unless the confidential information is not hidden that’s where we use PCA. In our project, we used the same dataset to compare legitimate and fraudulent transactions. In the end, we used a confusion matrix to see the number of transactions that were reported legitimate and were actually legitimate and the transactions which were reported fraudulent but were actually legitimate. Similarly, the transactions reported as fraudulent were actually legitimate and the transactions that were reported as fraudulent were actually fraudulent.
3.	Third application that we explained is noise reduction. Noise reduction is the process by which we reduce the extra unnecessary information in a dataset. For that, we used Kernal PCA.
PCA is a linear method. That is, it can only be applied to datasets that are linearly separable. It does an excellent job for datasets, which are linearly separable. But, if we use it for non-linear datasets, we might get a result that may not be the optimal dimensionality reduction. Kernel PCA uses a kernel function to project the dataset into a higher dimensional feature space, where it is linearly separable. It is similar to the idea of Support Vector Machines.
There are various kernel methods like linear, polynomial, and gaussian.
4.	Last application was anomaly detection. Anomaly detection is the identification of rare events, items, or observations that are suspicious because they differ significantly from standard behaviors or patterns. Anomalies in data are also called standard deviations, outliers, noise, novelties, and exceptions.
