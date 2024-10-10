# 信用卡欺诈检测 Credit Card Fraud Detection

## 背景 background

假设有一份信用卡交易记录，遗憾的是数据经过了脱敏处理，只知道其特征，却不知道每一个字段 代表什么含义，没关系，就当作是一个个数据特征。在数据中有两种类别，分别是正常交易数据和异常 交易数据，字段中有明确的标识符。要做的任务就是建立逻辑回归模型，以对这两类数据进行分类

Assume there is a set of credit card transaction records. Unfortunately, the data has been anonymized, so while we know the features, we don't know what each field represents. That's okay; we can treat them as individual data features. In the data, there are two categories: normal transaction data and fraudulent transaction data, and there is a clear identifier for each category. The task is to build a logistic regression model to classify these two types of data.

<br/>

<img width="815" alt="image" src="https://github.com/user-attachments/assets/fe2f9bdb-90cd-4555-ad4d-bfe1b2ce323c">

<br/>

<br/>


## 逻辑回归分类 logistic regression classification

下采样数据训练，跑真实数据验证

Train on Undersampled Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/030cd514-b87e-46b0-8d70-911c518e1773">

<br/>
<br/>


过采样数据训练，跑真实数据

Train on Oversampled Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/4f8fcc17-ee31-4ecb-8d49-c56c319e18f2">

<br/>
<br/>


真实数据训练，跑真实数据验证

Train on Real Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/af95a8ef-ef38-4cd9-bdfe-b4523411a73f">

<br/>

<br/>


## 神经网络分类 neural network classification

下采样数据训练，跑真实数据验证 

Train on Undersampled Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/6f0572af-9b19-4611-b1e6-860304c7f8e4">

<br/>
<br/>


过采样数据训练，跑真实数据 

Train on Oversampled Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/584b9cd7-c524-429e-94bd-a4ec670cc468">

<br/>
<br/>


真实数据训练，跑真实数据验证 

Train on Real Data, Validate on Real Data

<img width="350" alt="image" src="https://github.com/user-attachments/assets/497ca720-f08d-4d42-8dbe-d45b7aed6211">



