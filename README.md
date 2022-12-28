# Brain-Tumor-Detection
Brain tumor detection model, trained on a logistic regression model with 86% accuracy.

Dataset: https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection


# Formulas used:

$$z^{(i)} = w^T x^{(i)} + b \tag{Calculating output.}$$

$$\hat{y}^{(i)} = a^{(i)} = sigmoid(z^{(i)})\tag{Sigmoid activation function.}$$ 


$$ \mathcal{L}(a^{(i)}, y^{(i)}) =  - y^{(i)}  \log(a^{(i)}) - (1-y^{(i)} )  \log(1-a^{(i)})\tag{Cost function.}$$
