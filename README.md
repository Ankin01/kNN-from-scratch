# kNN-from-scratch
An implementation of the k-Nearest Neighbor Algorithm from scratch

This code assumes the presence of training data and testing data in separate files.

Further, as viewed the code assumes the use of common data preprocessing techniques 
                - Normalization (min-max or zscore)
                - Data Imputation (Use major categories appearing in a column, Use zero in columns of float/int, Use "" in                       cases where column is of type object)

The code compares different metrics:
                - AUC (Area Under Curve)
                - Accuracy
                - Brier score
