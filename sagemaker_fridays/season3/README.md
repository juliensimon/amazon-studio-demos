# 🎬 SageMaker Fridays - Season 3

[![AWS](https://img.shields.io/badge/AWS-SageMaker-orange?logo=amazon-aws)](https://aws.amazon.com/sagemaker/)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![YouTube](https://img.shields.io/badge/YouTube-Season%203-red?logo=youtube)](https://www.youtube.com/playlist?list=PLJgojBtbsuc1i4OGxxsWHxY-KeAYUFFbe)

Season 3 of SageMaker Fridays focuses on **Feature Engineering & AutoML**, covering essential machine learning workflows from data preprocessing to model deployment.

## 📁 Episodes

### 🎯 Episode 3 - Amazon Reviews Classification
**Folder**: [`s03e03/`](s03e03/)
- **01 - Preprocessing Amazon Reviews.ipynb** - Data preprocessing and feature engineering
- **02 - BlazingText on Amazon Reviews - Classification.ipynb** - Text classification with BlazingText
- **03 - Managing feature versions.ipynb** - Feature versioning and management
- **preprocessing.py** - Custom preprocessing script

**Skills**: NLP, Text Classification, Feature Engineering

### 🔧 Episode 4 - Feature Store & End-to-End Workflows
**Folder**: [`s03e04/`](s03e04/)
- **01 - Preprocessing Amazon Reviews.ipynb** - Data preprocessing
- **02 - Ingesting in SageMaker Feature Store.ipynb** - Feature Store integration
- **03 - Building a dataset.ipynb** - Dataset creation
- **04 - End to end workflow.ipynb** - Complete ML pipeline
- **05 - Working with model packages.ipynb** - Model packaging
- **06 - Working with pipeline executions.ipynb** - Pipeline management
- **07 - Deploy with CloudFormation.ipynb** - Infrastructure as code
- **08 - Cleaning up.ipynb** - Resource cleanup
- **endpoint-one-model.yml** - CloudFormation template
- **endpoint-two-models.yml** - Multi-model deployment
- **ingesting.py** - Feature ingestion script
- **preprocessing.py** - Data preprocessing script
- **querying.py** - Feature querying script

**Skills**: Feature Store, MLOps, CloudFormation, End-to-End Pipelines

### 🤗 Episode 5 - Hugging Face Integration & Sentiment Analysis
**Folder**: [`s03e05/`](s03e05/)
- **01 - Hugging Face - Hello World.ipynb** - Basic Hugging Face integration
- **02 - Preprocessing reviews.ipynb** - Text preprocessing for sentiment analysis
- **03 - Sentiment analysis with Hugging Face and SageMaker.ipynb** - Complete sentiment analysis pipeline
- **preprocessing.py** - Text preprocessing utilities
- **train.py** - Custom training script

**Skills**: Transformers, Hugging Face, Sentiment Analysis, Custom Training

### 🖼️ Episode 6 - Image Classification on ImageNet
**Folder**: [`s03e06/`](s03e06/)
- **01 - Prepare ImageNet.txt** - ImageNet dataset preparation
- **02 - Image Classification on Imagenet.ipynb** - Image classification with transfer learning

**Skills**: Computer Vision, Transfer Learning, ImageNet, Image Classification

### 🤖 Episode 7 - AutoGluon & AutoPilot
**Folder**: [`s03e07/`](s03e07/)
- **01 - Convert data to CSV.ipynb** - Data format conversion
- **02 - Launch an AutoPilot job.ipynb** - SageMaker AutoPilot
- **03 - AutoGluon.ipynb** - AutoGluon for automated ML
- **04 - AutoGluon in SageMaker Processing.ipynb** - Processing job integration
- **05 - Loading AutoGluon models.ipynb** - Model loading and inference
- **autogluon-tabular.py** - AutoGluon tabular script

**Skills**: AutoML, AutoGluon, SageMaker AutoPilot, Processing Jobs

### 📦 Episode 8 - Model Import/Export & Fargate Deployment
**Folder**: [`s03e08/`](s03e08/)
- **01 Import XGBoost.ipynb** - Importing XGBoost models
- **02 Import TensorFlow.ipynb** - Importing TensorFlow models
- **03 Export XGBoost.ipynb** - Exporting XGBoost models
- **04 Export TensorFlow.ipynb** - Exporting TensorFlow models
- **05 Export Image Classification.ipynb** - Image classification model export
- **06 Export TensorFlow to Fargate.ipynb** - Fargate deployment
- **fmnist.py** - Fashion MNIST training script
- **inference-fargate-tf230-sagemaker.json** - Fargate configuration
- **mnist_keras_tf.py** - MNIST training with TensorFlow
- **model.py** - Custom model definition
- **xgb-dm.py** - XGBoost DMatrix script
- **xgb-script.py** - XGBoost training script

**Skills**: Model Import/Export, Containerization, Fargate, Multi-Framework Support

## 🎯 Learning Objectives

### Core Skills
- **Feature Engineering**: Master SageMaker Feature Store and feature versioning
- **AutoML**: Learn AutoGluon and SageMaker AutoPilot for automated ML
- **Model Management**: Import/export models across frameworks
- **Deployment**: Deploy models using SageMaker endpoints and Fargate

### Advanced Topics
- **End-to-End Pipelines**: Build complete ML workflows
- **Infrastructure as Code**: Use CloudFormation for deployment
- **Custom Training**: Implement custom training scripts
- **Multi-Model Serving**: Deploy multiple models efficiently

## 🚀 Getting Started

### Beginner Path
1. Start with **s03e03** for basic text classification
2. Move to **s03e06** for image classification
3. Explore **s03e07** for AutoML concepts

### Intermediate Path
1. Dive into **s03e04** for feature engineering workflows
2. Try **s03e05** for Hugging Face integration
3. Experiment with **s03e08** for model management

### Advanced Path
1. Master **s03e04** end-to-end workflows
2. Customize **s03e05** training scripts
3. Optimize **s03e08** deployment strategies

## 🛠️ Prerequisites

- Amazon SageMaker Studio environment
- Basic Python and Jupyter notebook knowledge
- Understanding of machine learning concepts
- AWS account with appropriate permissions

## 📚 Key Technologies

- **SageMaker Feature Store**: Feature management and versioning
- **BlazingText**: Text classification algorithm
- **Hugging Face Transformers**: State-of-the-art NLP models
- **AutoGluon**: Automated machine learning
- **SageMaker AutoPilot**: AWS automated ML service
- **CloudFormation**: Infrastructure as code
- **AWS Fargate**: Serverless container deployment

## 🎥 Video Resources

- **Complete Season 3 Playlist**: [YouTube](https://www.youtube.com/playlist?list=PLJgojBtbsuc1i4OGxxsWHxY-KeAYUFFbe)
- **Individual Episodes**: Each episode folder contains specific video links

## 🔗 Additional Resources

- [SageMaker Feature Store Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/feature-store.html)
- [AutoGluon Documentation](https://auto.gluon.ai/)
- [Hugging Face SageMaker Integration](https://huggingface.co/docs/sagemaker)
- [SageMaker AutoPilot Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/autopilot.html)

## 🤝 Contributing

Contributions to improve Season 3 tutorials are welcome! Feel free to submit pull requests or open issues.

---

**Ready to master Feature Engineering & AutoML?** Start with Episode 3 and work your way through! 🚀 