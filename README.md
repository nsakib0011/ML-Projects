#A basic deep learning multiclass classification project based on CNN

Classification of traffic signs from a bunch of images, where 43 different classes are available. The Dataset used here is from Kaggle.
In the sequential model, I have used two convolutional layers followed by one pooling layer and then the normalization then again the same structure another time. For down sampling I used AveragePooling2D class and used ReLU (Rectifier Linear Unit) as the activation function.
I used two hidden layers follwed by normalization each time and for the final layer used Softmax activation function as this is a multiclass classification problem.
I used dropout to prevent my model from overfitting. Used a dropout rate of 0.3.
After training my model I got an accuracy rate of 94% which I think is quite good for a basic CNN.
