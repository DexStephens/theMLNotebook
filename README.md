# theMLNotebook

Taking time everyday in 2025 to better understand what ML foundations are, and how they are applied in Gen AI

Fundamentals of Machine Learning

- Supervised Learning: uses labeled datasets to train artificial intelligence algorithm models to identify the underlying patterns and relationships between input features and outputs. Goal: create a model that can predict correct outputs on new real-world data

Workflow:

1. get training data
2. Assemble data with labels
3. Separate into groups: training data, validation data, and test data
4. Choose an algorithm with which to create the model
5. Feed training dataset to selected algorithm
6. Validate and test model accordingly
7. Watch model performance and maintain accuracy with regular updates

Types of Supervised Learning

- Classification: uses an algorithm to sort data into categories. Recognizes and attempts to label or define these entities. Algorithms include: linear classifiers, support vector machines (SVM), decision trees, k-nearest neighbor and random forest
- Regression: used to understand the relationship between the dependent and independent variables. Algorithms include: linear regression, logistical regression, and polynomial regression

https://www.ibm.com/think/topics/supervised-learning

- Unsupervised Learning
- Semi-Supervised Learning
- Reinforcement Learning
- Bias-Variance Tradeoff

Vocabulary:

- Cross-Validation: the process of testing a model using a different portion of the dataset
- Data Bias: when the data is not representative of the real-world scenario the model is meant to operate in. Can result from how the data is collected, labeled, or sampled, leading to skewed or unfair outcomes
- Algorithmic Bias: when the model itself produces biased outputs, either due to its design or the interaction between the algorithm and the data. Even if the data is unbiased, the algorithm might amplify disparities or introduce new biases
- Dimensionality Reduction: reduces the number of features to those most crucial for predicting data labels, which preserves accuracy while increasing efficiency

Questions:

- How to regularly update supervised learning models?
- How do deep learning and machine learning relate?
  Deep learning is a subset of ML that uses neural networks with many layers (deep neural networks) to model complex patterns in large datasets. Effective for image recognition, natural language processing, and speech synthesis.

- How to simply explain how neural networks work?
  Neuron: a worker who is an expert at a certain thing
  Layers of Neurons: collectively combine neurons inputs (weighted answers) to determine the sole answer, which is passed on to the next layer to take into consideration
  Validation: gives final guess with weights associated with the different outcomes, and you can make the team smarter by letting them know what they got wrong, weights are adjusted, and guesses improve over time

Interesting:

- Many generative AI models are initially trained with unsupervised learning and later with supervised learning to increase domain expertise
