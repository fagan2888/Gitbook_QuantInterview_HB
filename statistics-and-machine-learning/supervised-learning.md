#### 

# Regression

#### Linear Regression

* Assumptions and intuition
  * when does the assumptions not important? \(when do analyze rather than prediction\)
    * indeed a projection from **y** to **X **vector space
  * diagnostics and treatments
    * fitted and residual plot
    * heteroskedasticity
    * co-linearity 
      * regularization via Lasso
      * PCA \(matrix transformation\)
* proof MLE Estimate &lt;=&gt; RSS Min Estimate
  * use p.d.f of $$\epsilon$$ on beta
* Derive beta
  * xy vs yx regression \(notice whose variance get "contributed averaged"\)
  * Single variable: min RSS = $$\sum (y_i - (\beta_1 x_i + \beta_0)$$
  * Muti-variable $$\mathbf{w^*} = (\mathbf{X^T X})^{-1} \mathbf{X^T y} $$
* Loss Function
  * Blue
  * Huber Loss Function
* Regularization
  * Ridge, Lasso \(Scarcity\)

#### Logistic Regression

* Intuition - Why do we have it
  * different contribution of large/small data
    * exponential family and penalize
  * assumption - Bernoulli distribution
    * odds, log odds
* Loss function derive parameter estimation
  * MLE - y is bernoulli function \(entropy loss\)
* Gradient Descent
  * entropy loss
  * MSE

# Tree-Based Model

Tree

* Algo
* Advantages
  * interaction handling
  * insensitivity to outliers

Tree Ensembling

* Random Forest
  * bagging 
    * bagging of data 
    * bagging of feature 
      * rule of sum - select sqrt\(k\) features
  * feature importance calculation
    * out-of-bag performance
* Advantage and Disadvantage
  * natural parallel \(embarrassed parallel algo\)
  * feature importance

# Support Vector Machine

* Hinge Loss
* Kernel Trick

## K-nearest Neighbor

* No Training stage
* higher  K is, more robust the model can be



## K means



