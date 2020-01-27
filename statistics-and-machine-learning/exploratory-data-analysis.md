## 

## 

## Feature Engineering

* label encoding
  * cardinal to ordinal bias
* one-hot-encoding
  * frequency-based encoding
* target encoding
  * integrating label information to itself, easy to overfit
    * separate part of data solely used for encoding 
* word2vec
* too many features
  * frequency-based encoding, target-encoding
  * hashing or clustering to combine features
* too sparse features

### Missing Value Handling

* Common Methods - Analyze Impact
  * Deletion
  * Imputation
* Categorical Features
  * Make NA as one category
  * Logistic Regression \(Model\)
* Continuous Features
  * Mean, Median, Mode, etc
  * Linear Regression
    * iterative
    * introduces some degree or correlation among features, but can me remediated by separating into sub-groups

### Feature Engineering Basics

* Imbalanced Feature
  * Upsampling 
  * Downsampling
* Spare Feature
  * Tree-based model are bad with sparse features
  * Use **Embeddings **to transfer higher dimensional data to lower dimensions
    * Tree based model + Logistic Regression/Neural Network



