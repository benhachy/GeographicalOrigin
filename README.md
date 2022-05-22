# PredictPosition

In this project, we use **genetic markers** to predict the **geographical origin** of an individual; individuals are Indians from America. We propose to build predictive linear models to predict the latitude and longitude of an individual from its genetic markers. Because the number of markers (p = 5709) is larger than the number of samples (n = 494), the predictors of the model will be the outputs of a **principal component analysis (PCA)** performed on the genetic markers. A genetic marker is encoded 1 if the individual has a mutation, 0 elsewhere.

To draw *geographical maps* in **R**, We used the **maps** and **fields** libraries.

This project has been done using the **R programming language** in a group of three people, at ENSIMAG
