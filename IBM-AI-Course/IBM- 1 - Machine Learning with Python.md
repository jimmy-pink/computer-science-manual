
## 🌟Course Introduction 🌟

### Pre-requisites
- Pandas
- NumPy
- Data preparation and data analysis with python

### What you will learn?
![[Pasted image 20250411140839.png]]

- Multiple linear regression
- Logistic regression
- Prediction
- Fraud Detection
- KNN and SVM

## M1:  ML Concepts

> Foundational machine learning concepts to delve deeper into applied machine learning modeling.


### Machine Learning

#### ML and DL 

Machine Learning :
- Using Algorithms
- Require Feature Engineering

Deep Learning:
- Using Multi-Layer Neural Network
- Automatically extract features

#### How machine learning work?

Teach computers to :
- learn from data
- identify patterns
- make decisions

Algorithms:
- Use computational methods for learning
- doesn't rely on a fixed algorithm

#### ML Paradigms

- **supervised learning models** :  train on labeled data 
- **unsupervised learning**:  works without labels.
- **semi-supervised learning**: works iteratively
- **reinforcement learning**: learns from feedback


### ML Techniques

![[Pasted image 20250411174710.png]]

- **classification**： predicts class or category of a case.
- **regression**:  predicts *continuous* values
- **clustering**： groups similar data
- **association**： finds items or events that co-occur
- **anomaly detection**: discovers abnormal and unusual cases
- **sequence mining**: predicts next event from ordered data
- **dimension reduction**: reduces size of data
- **recommendation systems** : associate people's preferences.

![[classsification-regression-clustering.png]]

### Applications of ML

![[Pasted image 20250411181921.png]]

#### Image Recognition with ML

> **Data**: Images of cats and dogs
> **Traditional Programming**: create rules to detect the animals
> **ML**: build a model to infer the animal type

![[Pasted image 20250411182233.png]]

#### Pairing ML with human intelligence

![[Pasted image 20250411182553.png]]

- chatbot
- face recognition
- computer games

### Machine Learning Model Lifecycle

#### Processes of the lifecycle

- **🔍 Problem Definition**  
- **📊 Data Collection**  
- **🧹 Data Preparation**  
	- clean data
	- **Explore data analysis**
	- **Train-Test Split**
- **🤖 Model Development**  
	- explore existing frameworks
	- content-based filtering
	- collaborative filtering
- ✅ **Model Evaluation**
- **🚀 Model Deployment**

### Tools for ML

![[Pasted image 20250411200005.png]]

#### Data

Data is a collection of:
-  raw facts
- figures
- information
used to draw insights, inform decisions, and fuel advanced technologies.
#### Common Languages for ML

- Python
	- analyzing and processing data
	- developing ML models
- R:
	- statistical learning
	- data exploration and ML
- Julia: parallel and distributed numerical computing support
- Scala： Processing big data and building ML pipelines
- Java： Support Scalable ML applications
- JavaScript: Running ML models in web browsers

#### Diff. types of ML tools

- Data processing and analytics
	- PostgreSQL 
	- Hadoop
	- Spark
	- Kafka
	- Pandas
	- NumPy
- Data Visualization
	- Matplotlib
	- Seaborn
	- ggplot2
	- Tableau
- Shallow Machine Learning
	- scipy: computing for optimization, integration and linear regression
	- scikit-learn: suite of classification, regression, clustering and dimensionality reduction
- Deep Learning
	- TensorFlow
	- Keras
	- Theano
	- PyTorch
- Computer Vision Application
	- OpenCV: real-time computer vision applications
	- Scikit-image: image processing algorithms
	- TorchVision: 
- Natural Language Processing
	- **NLTK**: text processing, tokenization, and stemming
	- TextBlob: part-of-speech tagging, noun phrase extraction, sentiment analysis, and translation
	- Stanza: pre-trained models for tasks such as NER and dependency parsing
- Generative AI tools
	- Hugging face transformers
	- DALL-E
	- PyTorch

### Sciki-Learn Library

- Free ML library for python
- Classification, Regression, Clustering, and Dimensionality reduction algorithms
- Designed to work with NumPy and SciPy
- Excellent documentation and community support
- Constantly evolving
- Enables easy implementation of ML models

#### Machine Learning pipeline tasks
![[Pasted image 20250411200910.png]]

#### Sk Learn Demo

- 标准化（Standardization）：
把特征转换成 **均值为 0，标准差为 1** 的分布，也叫 **Z-score 标准化**。
```python
X = np.array([[1], [2], [3], [4], [5]])
X_scaled = scaler.fit_transform(X)  
```
计算公式如下：
$$
X_{\text{scaled}} = \frac{X - \mu}{\sigma} , \mu 平均值，\sigma 为方差
$$
- 模型训练
线性回归 预测y=2x
```python
from sklearn.linear_model import LinearRegression  
import numpy as np  
  
# 训练数据  
X = np.array([[1], [2], [3], [4], [5]])  # 输入特征，必须是二维数组  
y = np.array([2, 4, 6, 8, 10])           # 标签（目标值）  
  
# 创建模型并训练  
model = LinearRegression()  
model.fit(X, y)  
# 使用模型进行预测  
y_pred = model.predict(np.array([[6], [7]])  )
```

## M2: Linear and Logistic Regression

>2 classical statistical methods:
> - linear regression
> - logistic regression


## M3: Building Supervised Learning Models


### M4: Building Unsupervised Learning Models


## M5:  Evaluating and Validating Machine Learning Models

## M6: Final Exam and Project
