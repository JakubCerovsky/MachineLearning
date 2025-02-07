# Machine Learning Notes

## Session 1 - Introduction

### Process

1. Data exploring to understand the collection
2. Split data to Train data and Test data - we cannot use the same data for training and testing (80/20 split - common)
   - Split Train data into Train Data and Validation data (80/20 split again)
   - Split both data into features and labels
   - Test data is one shot thing… You cannot use them again
3. If test accuracy is almost the same as train accuracy = good > if there is a big difference = bad (memorization)
   - Ideally the same
   - if not we tune some hyperparameters of the model to get better results

### Data

#### Labeled Data | Supervised Learning

- **Classification**

  - _y_ is a category
  - f.x. fraud detection, speech recognition, diagnostics

- **Regression**

  - _y_ is a number
  - f.x. age, high, price, weather forecasts, stock market predictions

#### Unlabeled Data | Unsupervised Learning

- **Clustering**

  - group similar objects
  - identify groups in data
  - f.x. targeted marketing, anomaly detection, image segmentation

- **Dimensionality Reduction**

  - reduce the amount of features
  - identify patterns in data
  - f.x. compression, structure discovery, big data visualization

## Algorithms

### kNN | Nearest Neighbour

Finds the nearest neighbour of the test data and assume the output will be the same (k by default 1).
However, we can define the k and tune the accuracy.
