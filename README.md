## Telco Churn Prediction with Neural Network
![telco](https://user-images.githubusercontent.com/36668856/134440389-5e0c8970-391d-4566-9ec0-c521f89680a7.png)

## Introduction

#### Dataset
Dataset berisi Perputaran Pelanggan Telekomunikasi dimana setiap baris mewakili pelanggan, setiap kolom berisi atribut pelanggan yang dijelaskan pada kolom Metadata.

#### Sumber Data
Data asli berasal dari kaggle : https://www.kaggle.com/blastchar/telco-customer-churn

#### Objective
Membuat model klasifikasi untuk melihat apakah Pelanggan berhenti berlangganan atau tidak dengan menggunakan Neural Network

#### Information
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

## Library
- pandas 
- numpy 
- matplotlib
- seaborn 

#### Feature Selection
- RandomForestClassifier

#### Pre-processing
- train_test_split 
- StandardScaler

#### Model training
- tensorflow 
- keras
- EarlyStopping
- Dropout

#### Hyperparameter tunning
- RandomizedSearchCV

#### Model Evaluation
- confusion_matrix 
- classification_report
- roc_curve, auc
- roc_auc_score

## Exploratory Data Analysis
![1](https://user-images.githubusercontent.com/36668856/134444720-3be761be-84b5-48a8-9d8a-ad8048d1c5d4.png)
![2](https://user-images.githubusercontent.com/36668856/134444719-9e2616d2-d85c-4572-935a-767428119337.png)
![3](https://user-images.githubusercontent.com/36668856/134444717-b3621800-da9f-4c91-a061-91286f6afdd7.png)
![4](https://user-images.githubusercontent.com/36668856/134444715-bdbbbe13-d328-4998-83ee-2d56393ca130.png)
![5](https://user-images.githubusercontent.com/36668856/134444743-9a4d7f1d-b180-4c86-bb05-4114e8ff0bf0.png)
![6](https://user-images.githubusercontent.com/36668856/134444754-5caafd33-7780-4764-9251-ac11ad37675a.png)
![7](https://user-images.githubusercontent.com/36668856/134444757-43a5386f-b4ea-4a62-b574-a95c9281d43d.png)
![8](https://user-images.githubusercontent.com/36668856/134444763-d30feb39-6ea8-4079-8772-b5a3ac0c1ba7.png)
![9](https://user-images.githubusercontent.com/36668856/134444771-ac8917f0-245d-4f58-bc27-3b56cb02c08b.png)
![10](https://user-images.githubusercontent.com/36668856/134444780-6fa26cb3-9c81-4281-8be1-e87898684abf.png)
![11](https://user-images.githubusercontent.com/36668856/134444798-c49d6143-5e82-402b-83da-97430f3caeab.png)
![12](https://user-images.githubusercontent.com/36668856/134444805-06a2b62f-1928-4c7c-bc8b-de3e09516a67.png)
![13](https://user-images.githubusercontent.com/36668856/134444811-f4fa7624-2062-4c02-aab3-a96ae24456fc.png)
![14](https://user-images.githubusercontent.com/36668856/134444819-85478d3b-94a6-4e97-ac38-5c80308b846d.png)
![15](https://user-images.githubusercontent.com/36668856/134444826-deef0728-1c79-4406-a724-99a9a0924b09.png)
![16](https://user-images.githubusercontent.com/36668856/134444829-95df60a0-87c5-4549-b30f-697587113553.png)
![17](https://user-images.githubusercontent.com/36668856/134444836-f6c21882-e460-43a3-911d-c2e4145e52ac.png)
![18](https://user-images.githubusercontent.com/36668856/134444844-12ade195-a59b-4d4d-9dea-5ec019510e03.png)
![19](https://user-images.githubusercontent.com/36668856/134444848-6c27b66a-8bda-4f57-a6ef-45872ab34c1c.png)
![20](https://user-images.githubusercontent.com/36668856/134444850-b1d7e821-6c9b-45e4-80c9-02ed322919cd.png)

## Features Selection
![features_selection](https://user-images.githubusercontent.com/36668856/134444921-deaa7eb2-0ce5-4e5a-bd04-0bd4a6de5b4d.png)

## Fit and Train Model
![fit trainmodel](https://user-images.githubusercontent.com/36668856/134444984-4e60c9cd-8043-4a58-a022-700a64fc4e00.png)
![model_evaluation2](https://user-images.githubusercontent.com/36668856/134445100-58b05a10-4301-413a-82f3-2c711e462619.png)

## Model Evaluation
![model_evaluation1](https://user-images.githubusercontent.com/36668856/134445093-61017031-01e8-409c-9e4e-c9993290f7f8.png)
![model_evaluation1 1](https://user-images.githubusercontent.com/36668856/134445096-fee4a347-a0d3-4f54-8338-9bbeaaace786.png)
