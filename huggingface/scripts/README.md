# 📜 Hugging Face Scripts

[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-yellow?logo=huggingface)](https://huggingface.co/)
[![AWS](https://img.shields.io/badge/AWS-SageMaker-orange?logo=amazon-aws)](https://aws.amazon.com/sagemaker/)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)

This folder contains custom training and inference scripts for integrating Hugging Face Transformers with Amazon SageMaker.

## 📁 Files

### 🚀 Training Scripts
- **`train.py`** - Custom training script for Hugging Face models in SageMaker

## 🎯 Script Details

### `train.py`
A comprehensive training script that demonstrates how to:
- Load pre-trained models from Hugging Face Hub
- Customize training configurations
- Handle data loading and preprocessing
- Implement custom training loops
- Save and export models for SageMaker deployment

#### Key Features
- **Model Loading**: Supports various Hugging Face model architectures
- **Data Processing**: Flexible data loading and preprocessing
- **Training Configuration**: Customizable hyperparameters and training settings
- **SageMaker Integration**: Optimized for SageMaker Training Jobs
- **Model Export**: Proper model saving for deployment

#### Usage
```bash
# Basic usage
python train.py --model_name bert-base-uncased --task classification

# With custom parameters
python train.py \
    --model_name distilbert-base-uncased \
    --task sentiment_analysis \
    --epochs 3 \
    --batch_size 16 \
    --learning_rate 2e-5
```

## 🛠️ Prerequisites

- Python 3.7+
- Transformers library
- PyTorch or TensorFlow
- SageMaker SDK
- Required datasets and model files

## 📚 Customization

### Adding New Models
1. Import the desired model from transformers
2. Update the model loading logic
3. Adjust preprocessing for your specific model
4. Test with your dataset

### Custom Training Loops
1. Modify the training loop in `train.py`
2. Add custom loss functions if needed
3. Implement custom evaluation metrics
4. Add logging and monitoring

### Data Preprocessing
1. Update data loading functions
2. Implement custom tokenization
3. Add data augmentation if needed
4. Handle different data formats

## 🔧 Integration with SageMaker

### Training Job Configuration
```python
from sagemaker.huggingface import HuggingFace

estimator = HuggingFace(
    entry_point='train.py',
    source_dir='scripts/',
    instance_type='ml.p3.2xlarge',
    role=role,
    transformers_version='4.17.0',
    pytorch_version='1.10.0',
    py_version='py38'
)
```

### Model Deployment
```python
from sagemaker.huggingface import HuggingFaceModel

model = HuggingFaceModel(
    model_data=estimator.model_data,
    role=role,
    transformers_version='4.17.0',
    pytorch_version='1.10.0',
    py_version='py38',
    entry_point='inference.py'
)
```

## 📖 Best Practices

### Script Organization
- Keep scripts modular and reusable
- Implement proper error handling
- Add comprehensive logging
- Include configuration validation

### Performance Optimization
- Use appropriate batch sizes
- Implement gradient accumulation for large models
- Optimize data loading with DataLoader
- Use mixed precision training when possible

### SageMaker Integration
- Follow SageMaker script requirements
- Implement proper model saving
- Handle SageMaker environment variables
- Test locally before deploying

## 🔗 Related Resources

- [Hugging Face Training Documentation](https://huggingface.co/docs/transformers/training)
- [SageMaker Hugging Face Containers](https://github.com/aws/sagemaker-huggingface-inference-toolkit)
- [Transformers Examples](https://github.com/huggingface/transformers/tree/master/examples)
- [SageMaker Training Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/train.html)

## 🤝 Contributing

Feel free to contribute additional training scripts or improvements to existing ones!

---

**Back to**: [Hugging Face Integration](../) 🤗 