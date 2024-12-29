# Vehicle-Silhouette-Classification


## Situation:

- This project attempted to classify four different kinds of vehicle silhouettes-double-decker bus, Chevrolet van, Saab 9000, and Opel Manta 400. Features of the cars were derived from these numeric features by the capture at different angles.
- High-dimensional feature space added difficulty for accurate vehicle classification, and it's tough especially with two models of car that were confusing between one and the other. 

## Task:

- Develop a strong vehicle classification model using techniques from machine learning.
- Implement dimensionality reduction using Principal Component Analysis (PCA), reducing the number of features while keeping the most relevant information.
- Train and test classification models on both original feature sets and PCA-transformation data.
- Compare the models trained with the original versus reduced feature sets to establish the effectiveness of dimensionality reduction.


## Action
- Applied PCA to determine the principal components that explain the maximum variance of the data.
- Decided on the number of principal components to retain based on the level of variance to be explained.
- Trained classification models such as SVM, k-NN, etc. on both the original and PCA-transformed data.
- Evaluated the model performance using metrics like accuracy, precision, recall, and F1-score.
- Annotated the results to see the effects of PCA on the model's performance and identify the optimal number of features to use for classification.


## Result:

- Developed and evaluated vehicle classification models based on original and PCA-transformed features.
- Observed 30% slight improvement in classification accuracy classi by using PCA-transformed data over the original data.
- Illustrated the applicability of PCA in dimensionality reduction without loss or gain in classification performance.
- I gained valuable insights into the impact of feature selection and dimensionality reduction on machine learning model performance.
