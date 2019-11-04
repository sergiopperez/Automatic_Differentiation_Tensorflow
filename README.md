# Automatic differentiation for linear regression in Tensorflow


__Objective__: apply automatic differentiation to train a linear regression layer defined with model subclassing in Tensorflow.

Linear noisy data is initially created to serve as training data. Subsequently model subclassing is applied to define the linear regression layer to train. Finally the tf.GradientTape() is employed to obtain the gradients for the training loop.

![images](/image/lr.png)


