# Performance Evaluation on USPS Dataset

This page shows the performance of various feature
selection methods using Classification Accuracy, 
Stability and Robustness on USPS Dataset.

Statistical Based Methods
---------------------------------------
**Classification Accuracy:**

T-score is used for binary classifications.

Gini Index is unable to get scores.

**Stability:**

**Robustness:**


Similarity Based Methods
-----------------------------------
**Classification Accuracy:**

![](https://github.com/ZixiaoShen/Performance-Comparison-of-Feature-Selection-Methods/blob/master/USPS/Similarity_Based/Acc_Similarity_FS.png)

**Stability:**

Laplacian Score: 0.4922

ReliefF: 0.3299

**Robustness:**

![](https://github.com/ZixiaoShen/Performance-Comparison-of-Feature-Selection-Methods/blob/master/USPS/Similarity_Based/Robust_Similarity_FS.png)

Information Theoretical Based Methods
-----------------------------------------
**Classification Accuracy:**

![](https://github.com/ZixiaoShen/Performance-Comparison-of-Feature-Selection-Methods/blob/master/USPS/Information_Based/Acc_Information_FS.png)

**Stability:**

MIFS: 0.3156

**Robustness:**

![](https://github.com/ZixiaoShen/Performance-Comparison-of-Feature-Selection-Methods/blob/master/USPS/Information_Based/Robust_Information_FS.png)

Sparse Learning Based Methods
-----------------------------------
**Classification Accuracy:**

It is very time consuming to run the program as it
is not a filter feature selection method.

Graph Based Methods
--------------------------------------
**Classification Accuracy:**


**Stability:**

IFS: 0.0150

**Robustness:**

