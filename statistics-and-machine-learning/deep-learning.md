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
   1. effect of convolution \(edge detection\)
   2. effect of pooling
      1. parameter sharing, feature sparsity 
      2. translation invariance
2. Modern CNN
   1. LeNet \(LeNet-5\)
3. CNN Training
   1. weight initilization
   2. activation function
      1. Vanishing Gradient and Exploding Gradient
         1. sigmoid
         2. tanh
         3. ReLU



