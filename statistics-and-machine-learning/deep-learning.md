## Model Training

#### Optimization

1. Gradient Descent
   1. Derive: Linear, Logistic Regression
      1. Newton's Method derive
   2. Stochastic Gradient Descent
      1. Mini-batch gradient descent
      2. Momentum on Gradient
         1. \($$w_t = w_{t-1} - h_t, h_t = \alpha h_{t-1} + \eta_t g_t)$$
         2. Adaptive Methods to eliminate learning rates sensitivity
            1. Nesterov Momentum
            2. AdaGrad
            3. RMSprop
            4. Adam
   3. Neutral Network Training
      1. Multi-layer perceptron backward propagation
         1. Implementation
         2. Jacobian

## Convolutional Neural Network

1. Convolution and Pooling  
   1. what is convolution and effect of convolution \(edge detection\)

   1. what is pooling and the effect of pooling
      1. parameter sharing, feature sparsity 
      2. translation invariance
      3. how to back-propagate on pooling layer

2. Modern CNN
   1. LeNet \(LeNet-5\)
   2. AlexNet\(2012\)
   3. VGG\(2015\)
   4. Inception V3\(2015\)
      1. inception block
         1. 1x1 convolutions
            1. reduce the number of channels and not hurting the quality of the model
            2. model Gaussian blur filter
            3. filter decomposition
               1. nxn replaced with 1xn and nx1
   5. ResNet \(2015\)
      1. residual connections
3. CNN Training
   1. weight initilization
      1. criterion
         1. E\(sum\(x_i w_\_i\)\) = 0
         2. Var\(sum\(xiwi\)\) = 1
      2. Types
         1. Xavier initialization
         2. He Initilization
   2. activation function
      1. Vanishing Gradient and Exploding Gradient
         1. sigmoid
         2. tanh
         3. ReLU
         4. Leaky ReLU
      2. evaluate activation functions
         1. gradient fast to compute
         2. gradient vanishing/exploding
         3. faster convergence
         4. zero-centered
         5. dying neuron \(dying ReLU\)
      3. Batch Normalization
         1. estimate mu and sigma \(exponential smoothing\)
         2. normalize neuron output before activation
      4. Regularization
         1. dropout
            1. training a neuron present with probability p
            2. testing always present
         2. data augmentation



