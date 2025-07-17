# 🤗 Hugging Face Integration with SageMaker

[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Transformers-yellow?logo=huggingface)](https://huggingface.co/)
[![AWS](https://img.shields.io/badge/AWS-SageMaker-orange?logo=amazon-aws)](https://aws.amazon.com/sagemaker/)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)

This folder contains examples and tutorials for integrating Hugging Face Transformers with Amazon SageMaker, demonstrating how to leverage state-of-the-art pre-trained models in your ML workflows.

## 📁 Contents

### 🚀 Getting Started
- [`Hugging Face - Hello World.ipynb`](Hugging%20Face%20-%20Hello%20World.ipynb) - Basic introduction to Hugging Face with SageMaker
- [`Hugging Face - SageMaker.ipynb`](Hugging%20Face%20-%20SageMaker.ipynb) - Advanced SageMaker integration examples

### 📜 Scripts
- [`scripts/`](scripts/) - Training and inference scripts
  - [`train.py`](scripts/train.py) - Custom training script for Hugging Face models

## 🎯 What You'll Learn

### Basic Integration
- Loading pre-trained models from Hugging Face Hub
- Tokenization and text preprocessing
- Basic inference with SageMaker endpoints

### Advanced Workflows
- Custom training with Hugging Face models
- Fine-tuning on custom datasets
- Model deployment and serving
- Batch inference and processing

## 🛠️ Prerequisites

- Amazon SageMaker Studio environment
- Hugging Face `transformers` library
- Basic knowledge of PyTorch or TensorFlow
- Understanding of transformer models

## 🚀 Quick Start

1. **Install Dependencies:**
   ```bash
   pip install transformers torch sagemaker
   ```

2. **Start with Hello World:**
   - Open `Hugging Face - Hello World.ipynb`
   - Follow the step-by-step instructions

3. **Explore Advanced Examples:**
   - Dive into `Hugging Face - SageMaker.ipynb`
   - Experiment with custom training scripts

## 📚 Key Concepts

### Hugging Face Transformers
- Pre-trained language models (BERT, GPT, T5, etc.)
- Tokenizers and text preprocessing
- Model pipelines for common NLP tasks

### SageMaker Integration
- SageMaker Training Jobs with custom containers
- SageMaker Endpoints for model serving
- SageMaker Processing for data preprocessing
- Model registry and versioning

## 🔧 Common Use Cases

1. **Text Classification**
   - Sentiment analysis
   - Topic classification
   - Intent detection

2. **Text Generation**
   - Language modeling
   - Text summarization
   - Question answering

3. **Named Entity Recognition**
   - Entity extraction
   - Information extraction

4. **Translation**
   - Machine translation
   - Cross-lingual tasks

## 📖 Learning Path

### Beginner
1. Start with `Hugging Face - Hello World.ipynb`
2. Understand basic tokenization and model loading
3. Try simple inference examples

### Intermediate
1. Explore `Hugging Face - SageMaker.ipynb`
2. Learn about custom training workflows
3. Experiment with different model architectures

### Advanced
1. Customize training scripts in `scripts/`
2. Implement custom preprocessing pipelines
3. Optimize for production deployment

## 🎥 Related Videos

- [SageMaker Studio Demos Playlist](https://www.youtube.com/playlist?list=PLJgojBtbsuc0MjdtpJPo4g4PL8mMsd2nK)
- [SageMaker Fridays - Hugging Face Episodes](https://www.youtube.com/playlist?list=PLJgojBtbsuc1i4OGxxsWHxY-KeAYUFFbe)

## 🔗 Useful Resources

- [Hugging Face Documentation](https://huggingface.co/docs)
- [SageMaker Hugging Face Containers](https://github.com/aws/sagemaker-huggingface-inference-toolkit)
- [Transformers Examples](https://github.com/huggingface/transformers/tree/master/examples)
- [SageMaker Training Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/train.html)

## 🤝 Contributing

Feel free to contribute additional examples or improvements to the Hugging Face integration tutorials!

---

**Next Steps**: Explore the [SageMaker Fridays](../sagemaker_fridays/) series for more advanced ML workflows! 