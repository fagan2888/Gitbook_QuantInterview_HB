# Supervised Learning Questions

## Model Training and General Questions

1. Bias Variance Decomposition

## Regression

---

### Linear Regression

1. Assumptions and intuition
   * when do the assumptions not important? \(when do analyze rather than prediction\)
     * indeed a projection from **y** to **X **vector space
   * diagnostics and treatments
     * fitted and residual plot
     * heteroskedasticity
     * co-linearity 
       * regularization via Lasso
       * PCA \(matrix transformation\)
2. MLE and OLS
   1. compare difference
   2. proof MLE Estimate &lt;=&gt; RSS Min Estimate
   3. use p.d.f of $$\epsilon$$ on beta
3. Derive
   * xy vs yx regression \(notice whose variance get "contributed averaged"\)
   * Single variable max MLE - min RSS = $$\sum (y_i - (\beta_1 x_i + \beta_0))^2$$
   * Muti-variable $$\mathbf{w^*} = (\mathbf{X^T X})^{-1} \mathbf{X^T y} $$
4. Loss Function
   * proof: min Loss is solution for linear problem \(MLE/OLS\)
   * Blue
   * Other loss functions
     * Absolute Loss
     * Huber Loss Function
5. Regularization
   * Ridge, Lasso \(Scarcity\)

---

### Logistic Regression

1. Intuition - Why do we have it

   * different contribution of large/small data
     * exponential family and penalize
   * assumption - Bernoulli distribution
     * odds, log odds

2. Loss function derive parameter estimation

   * MLE - y is bernoulli function \(entropy loss\)

3. implement Gradient Descent

   * entropy loss \(Bernoulli MLE Loss\)
   * Mean Square Loss

# Classification

1. Confusion Matrix and Model Evaluation
   * Precision, Recall
   * Accuracy
   * ROC Curve
   * 
2. how to do multi-class calssification
   * multiple binary classficiation
   * softmax

## Tree-Based Model

### Tree

* Algo
  * ID3
  * ID4.5
  * CART
    * Hyperparamters
      * max\__depth, min\_\_samples\_\_split, min\_samples\_leaf, max\_leaf\_nodes\_
* Loss
  * entropy
  * Gini Index
* Advantages
  * interaction handling
  * insensitivity to outliers

### Tree Ensembling

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

### Support Vector Machine

* Hinge Loss
* Kernel Trick

### K-nearest Neighbor

* No Training stage
* higher  K is, more robust the model can be



