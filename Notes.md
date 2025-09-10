# Preface

**Roadmap**  

Fundamental ML Algorithms (Scikit-Learn):  

* Linear and Polynomial Regression  
* Logistic Regression  
* K-nearest Neighbors  
* Support Vector Machines    
* Decision Trees  
* Random Forests  
* Ensemble Methods  
* Clustering  
* Density Estimation  
* Anomaly Detection  

NN and DL (TensorFlow):  

* Feedforward NN  
* Convolutional NN  
* Encoder-Decoders and Transformers  
* Generative Adversarial networks  
* Diffusive Models  

**Examples of Applications**

*  Image classification: CNN  
*  Semantic image segmentation: CNN, transformers  
*  Text classification: NLP  
*  Text summarization: NLP
*  Speech recognition: RNN, CNN, transformers
*  Anomaly detection: isolation forests, Gaussian mixture models, autoencoders
*  Clustering: k-means, DBSCAN
*  Data visualization: dimensionality reduction
*  Recommender system: ANN
*  Agents: reinforcement learning

**Training Supervision**

- Supervised learning: training set includes labels, e.g., classification and prediction
- Unsupervised learning: unlabeled data, e.g., clustering, data visualization, dimensionality reduction, anomaly detection/novelty detection, association rule learning
- Semi-supervised learning: partially labeled data, combination of supervised and unsupervised algorithms
- Self-supervised learning: generating a fully labeled dataset from a fully unlabeled one
- Reinforcement learning: agent learning by itself, e.g., robots

**Batch v. s. Online Learning**

- Batch learning: trained using all available data, incapable of learning incrementally, offline learning
- Online learning: sequential data feeding, good for fast-changing systems, limited computing resources, or extremely large datasets

**Instance-Based v. s. Model-Based Learning**

- Instance-based learning: generalize to new cases by using a similarity measure to learned examples
- Model-based learning: build a model to make predictions on new cases

**Main Challenges of ML**

“Bad Data”

- Insufficient training data
- Nonrepresentative training data
- Poor-quality data
- Irrelevant features

“Bad Algorithms”

- Overfitting: happens when the model is too complex relative to the amount and noisiness of the training data. Solutions: model simplification through regularization, more training data, noise reduction.
- Underfitting: happens when the model is too simple to learn the underlying structure of the data. Solutions: more powerful model with more parameters, feed better feature engineering, reduce the constraints

# End-to-End Machine Learning Project

Dataset: CA housing prices dataset from the StatLib repository

Objective: prediction on  the median housing price of any district

Cost function: RMSE

> [!NOTE]
>
> Page 45 - Definition of $l_k$ norm

