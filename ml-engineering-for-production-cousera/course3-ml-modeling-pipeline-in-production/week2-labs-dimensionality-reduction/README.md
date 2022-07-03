# Labs: Dimensionality Reduction
**Lab 1 - Manual Feature Engineering (`C3_W2_Lab_1_Manual_Dimensionality.ipynb.ipynb`)**: 
 In this lab we are going to perform feature engineering using TensorFlow and Keras. In particular, we will:
1. Define the model using feature columns.
2. Use Lambda layers to perform feature engineering on some of these features.
3. Compare the training history and predictions of the model before and after feature engineering.

**Lab 2 - Algorithmic Dimensionality Reduction (`.ipybn`)**: In this lab, we are going to perform several algorithms that aim to reduce the dimensionality of data. This topic is very important because it is not uncommon that reduced models outperform the ones trained on the raw data because noise and redundant information are present in most datasets. This will also allow the reduced models to train and make predictions faster, which might be really important depending on the problem we are working on. In particular, we will:
- Use Principal Component Analysis (PCA) to reduce the dimensionality of a dataset that classifies celestial bodies
- Use Single Value Decomposition (SVD) to create low level representations of images of handwritten digits
- Use Non-negative Matrix Factorization (NMF) to segment text into topics

## Requirements
### Lab 1
`tensorflow==2.8.2`  
`pandas==1.3.5`

### Lab 2
`numpy==1.21.6`  
`pandas==1.3.5`  
`sklearn==1.0.2`