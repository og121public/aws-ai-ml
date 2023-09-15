# AWS AI/ML domains:

#### 1. Data Engineering
#### 2. Exploratory Data Analysis
#### 3. Modeling
#### 4. AI/ML Implementation and Operations

## 1: Data Engineering

### 1.1: Create data repositories for ML.

- Identify data sources (for example, content and location, primary
    sources such as user data).
- Determine storage mediums (for example, databases, Amazon S3, Amazon
    Elastic File System \[Amazon EFS\], Amazon Elastic Block Store \[Amazon EBS\]).

### 1.2: Identify and implement a data ingestion solution.

- Identify data job styles and job types (for example, batch load, streaming).
- Orchestrate data ingestion pipelines (batch-based ML workloads and
    streaming-based ML workloads).
  - Amazon Kinesis
  - Amazon Kinesis Data Analytics
  - Amazon Kinesis Data Firehose
  - Amazon EMR
  - AWS Glue
- Schedule jobs.

### 1.3: Identify and implement a data transformation solution.

- Transform data in transit (ETL, AWS Glue, Amazon EMR, AWS Batch).
- Handle ML-specific data by using MapReduce (for example, Apache Hadoop, Apache Spark, Apache Hive).

## 2: Exploratory Data Analysis

### 2.1: Sanitize and prepare data for modeling.

- Identify and handle missing data, corrupt data, and stop words.
- Format, normalize, augment, and scale data.
- Determine whether there is sufficient labeled data.
  - Identify mitigation strategies.
  - Use data labelling tools (for example, Amazon Mechanical Turk).

### 2.2: Perform feature engineering.

- Identify and extract features from datasets, including from data
 sources such as text, speech, image, public datasets.
- Analyze and evaluate feature engineering concepts (for example,
    binning, tokenization, outliers, synthetic features, one-hot
    encoding, reducing dimenionality of data).

### 2.3: Analyze and visualize data for ML.

- Create graphs (for example, scatter plots, time series, histograms,
    box plots).
- Interpret descriptive statistics (for example, correlation, summary
    statistics, p-value).
- Perform cluster analysis (for example, hierarchical, diagnosis,
    elbow plot, cluster size).

## 3: Modeling

### 3.1: Frame business problems as ML problems.

- Determine when to use and when not to use ML.
- Know the difference between supervised and unsupervised learning.
- Select from among classification, regression, forecasting,
    clustering, and recommendation models.

### 3.2: Select the appropriate model(s) for a given ML problem.

- XGBoost, logistic regression, k-means, linear regression, decision
    trees, random forests, RNN, CNN, ensemble, transfer learning
- Express the intuition behind models.

### 3.3: Train ML models.

- Split data between training and validation (for example, cross validation).
- Understand optimization techniques for ML training (for example,
    gradient decent, loss functions, convergence).
- Choose appropriate compute resources (for example GPU or CPU,
    distributed or non-distributed).
  - Choose appropriate compute platforms (Spark or non-Spark).
- Update and retrain models.
  - Batch or real-time/online

### 3.4: Perform hyperparameter optimization.

- Perform regularization.
  - Drop out
  - L1/L2
- Perform cross validation.
- Initialize models.
- Understand neural network architecture (layers and nodes), learning
    rate, and activation functions.
- Understand tree-based models (number of trees, number of levels).
- Understand linear models (learning rate).

### 3.5: Evaluate ML models.

- Avoid overfitting or underfitting.
  - Detect and handle bias and variance.
- Evaluate metrics (area under curve \[AUC\]-receiver operating
    characteristics \[ROC\], accuracy, precision, recall, Root Mean
    Square Error \[RMSE\], F1 score).
- Interpret confusion matrices.
- Perform offline and online model evaluation (A/B testing).
- Compare models by using metrics (for example, time to train a model, quality of model, engineering costs).
- Perform cross validation.

## 4: AI/ML Implementation and Operations
### 4.1: Build ML solutions for performance, availability, scalability,
resiliency, and fault tolerance.

- Log and monitor AWS environments.
  - AWS CloudTrail and Amazon CloudWatch
  - Build error monitoring solutions.
- Deploy to multiple AWS Regions and multiple Availability Zones.
- Create AMIs and golden images.
- Create Docker containers.
- Deploy Auto Scaling groups.
- Rightsize resources (for example, instances, Provisioned IOPS, volumes).
- Perform load balancing.
- Follow AWS best practices.

### 4.2: Recommend and implement the appropriate ML services and features for a given problem.

- ML on AWS (application services)
  - Amazon Polly
  - Amazon Lex
  - Amazon Transcribe
- Understand AWS service quotas.
- Determine when to build custom models and when to use Amazon
    SageMaker built-in algorithms.
- Understand AWS infrastructure (for example, instance types) and cost
    considerations.
  - Use Spot Instances to train deep learning models by using AWS Batch.

### 4.3: Apply basic AWS security practices to ML solutions.

- AWS Identity and Access Management (IAM)
- S3 bucket policies
- Security groups
- VPCs
- Encryption and anonymization

### 4.4: Deploy and operationalize ML solutions.

- Expose endpoints and interact with them.
- Understand ML models.
- Perform A/B testing.
- Retrain pipelines.
- Debug and troubleshoot ML models.
  - Detect and mitigate drops in performance.
  - Monitor performance of the model.

### 4.5: Related technologies:

- Ingestion/collection
- Processing/ETL
- Data analysis/visualization
- Model training
- Model deployment/inference
- Operationalizing ML
- AWS ML application services
- Language relevant to ML (for example, Python, Java, Scala, R, SQL)
- Notebooks and integrated development environments (IDEs)

## IN-SCOPE AWS services

The following list contains AWS services and features that are in scope
for the exam. This list is non-exhaustive and is subject to change. AWS
offerings appear in categories that align with the offerings' primary functions:

#### Analytics:

- Amazon Athena
- Amazon EMR
- AWS Glue
- Amazon Kinesis
- Amazon Kinesis Data Analytics
- Amazon Kinesis Data Firehose
- Amazon Kinesis Data Streams
- Amazon QuickSight

#### Compute:

- AWS Batch
- Amazon EC2
- AWS Lambda

#### Containers:

- Amazon Elastic Container Registry (Amazon ECR)
- Amazon Elastic Container Service (Amazon ECS)
- Amazon Elastic Kubernetes Service (Amazon EKS)
- AWS Fargate

#### Database:

- Amazon Redshift

#### Internet of Things:

- AWS IoT Greengrass

#### Machine Learning:

- Amazon Comprehend
- AWS Deep Learning AMIs (DLAMI)
- AWS DeepLens
- Amazon Forecast
- Amazon Fraud Detector
- Amazon Lex
- Amazon Mechanical Turk
- Amazon Polly
- Amazon Rekognition
- Amazon SageMaker
- Amazon Textract
- Amazon Transcribe
- Amazon Translate

#### Management and Governance:

- AWS CloudTrail
- Amazon CloudWatch
Networking and Content Delivery:
- Amazon VPC
Security, Identity, and Compliance:
- AWS Identity and Access Management (IAM)

#### Storage:
- Amazon Elastic Block Store (Amazon EBS)
- Amazon Elastic File System (Amazon EFS)
- Amazon FSx
- Amazon S3
