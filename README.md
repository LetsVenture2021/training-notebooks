# Hugging Face Training Notebooks 🤗

A comprehensive collection of Jupyter notebooks for learning and using Hugging Face libraries including Transformers, Diffusers, Datasets, PEFT, and more.

## 📚 Overview

This repository contains over **1,400 Jupyter notebooks** covering various aspects of machine learning with Hugging Face libraries. These notebooks range from beginner tutorials to advanced training examples, covering natural language processing, computer vision, audio processing, and more.

## 📂 Repository Structure

The repository is organized into the following main directories:

### 🎓 **course/**
Official Hugging Face Course notebooks in multiple languages. These are structured learning materials covering:
- Introduction to Transformers
- Using 🤗 Transformers
- Fine-tuning a pretrained model
- Sharing models and tokenizers
- The 🤗 Datasets library
- The 🤗 Tokenizers library
- Advanced NLP tasks

**Languages available:** English (en), Spanish (es), French (fr), German (de), Italian (it), Japanese (ja), Korean (ko), Portuguese (pt), Russian (ru), Chinese (zh-CN), Hindi (hi), Vietnamese (vi), Thai (th), and more.

### 💡 **examples/**
Practical examples demonstrating various tasks:
- **NLP Tasks:** Text classification, question answering, summarization, translation, language modeling
- **Computer Vision:** Image classification, semantic segmentation, object detection
- **Audio:** Speech recognition, audio classification
- **Multimodal:** Image captioning, visual question answering
- **Time Series:** Forecasting with Transformers
- **Biology:** Protein folding, DNA sequence modeling

### ☁️ **sagemaker/**
AWS SageMaker integration examples (30+ notebooks):
- Distributed training (data parallelism, model parallelism)
- Model deployment and inference
- Training with spot instances
- Batch transform inference
- Auto-scaling deployments
- Training with AWS Training Compiler
- Inferentia/Inferentia2 deployment
- Large language model deployment

### 🎨 **diffusers/** & **diffusers_doc/**
Stable Diffusion and image generation examples:
- Text-to-image generation
- Image-to-image translation
- Inpainting and outpainting
- Custom diffusion models

### 🔧 **peft/** & **peft_docs/**
Parameter-Efficient Fine-Tuning (PEFT) examples:
- LoRA (Low-Rank Adaptation)
- Prefix tuning
- P-tuning
- Adapter methods

### 📊 **datasets_doc/** & **datasets-server_doc/**
Examples for using the 🤗 Datasets library:
- Loading datasets
- Processing and transforming data
- Creating custom datasets
- Dataset streaming

### 🤖 **transformers_doc/**
Comprehensive Transformers library documentation notebooks:
- Preprocessing
- Training
- Model summaries
- Tokenization
- Multilingual models
- Available in multiple languages

### 🧩 **Other Directories:**
- **huggingface_hub/**: Hub API usage examples
- **safetensors_doc/**: SafeTensors format documentation
- **setfit_doc/**: SetFit (few-shot learning) examples
- **smolagents_doc/**: Agent framework examples
- **lerobot/**: Robotics examples
- **longform-qa/**: Long-form question answering
- **utils/**: Utility scripts for converting documentation to notebooks

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Basic understanding of Python and machine learning concepts

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LetsVenture2021/training-notebooks.git
   cd training-notebooks
   ```

2. **Install Jupyter:**
   ```bash
   pip install jupyter
   ```

3. **Install required libraries:**
   Most notebooks include installation cells at the beginning. Common libraries include:
   ```bash
   pip install transformers datasets torch torchvision torchaudio
   # For specific use cases:
   pip install diffusers accelerate peft
   pip install sagemaker  # For AWS SageMaker examples
   ```

### Running Notebooks

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Navigate to the notebook you want to run** based on your interest area (course/, examples/, sagemaker/, etc.)

3. **Follow the instructions in each notebook** - most include setup cells and step-by-step explanations

## 📖 How to Use This Repository

### For Beginners

Start with the **course/** directory:
1. Navigate to `course/en/chapter1/` for English content
2. Follow chapters sequentially for a structured learning path
3. Each chapter builds on previous concepts

### For Specific Tasks

Browse the **examples/** directory:
- Find notebooks by task name (e.g., `text_classification.ipynb`, `image_classification.ipynb`)
- Most examples include both PyTorch and TensorFlow versions
- Look for `-tf.ipynb` suffix for TensorFlow versions

### For AWS SageMaker Users

Explore the **sagemaker/** directory:
- Each subdirectory is numbered and named by use case
- Includes distributed training, deployment, and optimization examples
- Requires AWS account and SageMaker setup

### For Advanced Users

Check out specialized directories:
- **peft/**: For efficient fine-tuning of large models
- **diffusers/**: For generative AI and image synthesis
- **lerobot/**: For robotics applications
- **longform-qa/**: For advanced NLP tasks

## 🛠️ Utility Scripts

### Converting Documentation to Notebooks

The repository includes a utility for converting RST documentation to Jupyter notebooks:

```bash
make doc-notebooks
# or
python utils/convert_doc_to_notebooks.py
```

This script converts Hugging Face documentation pages into interactive notebooks.

## 🌟 Key Features

- **1,400+ notebooks** covering diverse ML tasks
- **Multi-language support** for educational content
- **Multiple frameworks** (PyTorch, TensorFlow, JAX)
- **Cloud integration** (AWS SageMaker)
- **Latest techniques** (PEFT, Diffusers, Agents)
- **Practical examples** with real datasets
- **Regular updates** with newest features

## 💻 Running in the Cloud

### Google Colab
Most notebooks can run in Google Colab:
1. Upload the notebook to Google Colab
2. Run the installation cells
3. Add GPU runtime if needed (Runtime → Change runtime type → GPU)

### AWS SageMaker Studio
For SageMaker notebooks:
1. Upload to SageMaker Studio
2. Follow the notebook's specific instructions
3. Ensure proper IAM roles and permissions

### Other Platforms
- **Kaggle Notebooks**: Upload and run with free GPU/TPU
- **Paperspace Gradient**: Import notebooks directly
- **Azure ML**: Compatible with Azure ML notebooks

## 🤝 Contributing

Contributions are welcome! If you'd like to add new notebooks or improve existing ones:
1. Fork the repository
2. Create a new branch for your changes
3. Add your notebook with clear documentation
4. Submit a pull request

## 📄 License

This repository is licensed under the Apache License 2.0. See [LICENSE](LICENSE) file for details.

## 🔗 Related Resources

- [Hugging Face Documentation](https://huggingface.co/docs)
- [Hugging Face Course](https://huggingface.co/course)
- [Hugging Face Forums](https://discuss.huggingface.co/)
- [Transformers GitHub](https://github.com/huggingface/transformers)
- [Diffusers GitHub](https://github.com/huggingface/diffusers)
- [Datasets GitHub](https://github.com/huggingface/datasets)

## 🆘 Getting Help

- **Issues**: Open an issue in this repository for notebook-specific problems
- **Discussions**: Use [Hugging Face Forums](https://discuss.huggingface.co/) for general questions
- **Documentation**: Check [Hugging Face Docs](https://huggingface.co/docs) for library documentation

## ⭐ Popular Notebooks

Some frequently used notebooks to get started:

- `examples/text_classification.ipynb` - Basic text classification
- `course/en/chapter1/` - Introduction to Transformers
- `sagemaker/01_getting_started_pytorch/` - SageMaker basics
- `examples/image_classification.ipynb` - Vision tasks
- `peft/` - Efficient fine-tuning techniques

---

Happy Learning! 🎉

For updates and news, follow [@huggingface](https://twitter.com/huggingface) on Twitter.
