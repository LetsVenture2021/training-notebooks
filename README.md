# 🤗 Hugging Face Training Notebooks

Welcome! This repository contains **1,494 Jupyter notebooks** demonstrating how to use various Hugging Face libraries including Transformers, Diffusers, Datasets, PEFT, SageMaker integration, and more.

## 📚 Repository Structure

This repository is organized into the following main directories:

### 🎓 **course/** 
Notebooks from the [Hugging Face Course](https://huggingface.co/course) available in multiple languages (English, Spanish, French, Italian, German, Hindi, Farsi, etc.). These notebooks cover fundamental concepts of NLP and machine learning with Transformers.

### 📖 **transformers_doc/** 
Auto-generated notebooks from the [🤗 Transformers documentation](https://huggingface.co/transformers/). These provide hands-on examples for all major Transformers features and models.

### 🎨 **diffusers/** & **diffusers_doc/**
Notebooks demonstrating image generation and manipulation using [🤗 Diffusers](https://github.com/huggingface/diffusers), including:
- Stable Diffusion tutorials
- ControlNet examples
- DreamBooth training
- Image-to-image generation
- And many more!

### 💾 **datasets_doc/**
Notebooks for working with the [🤗 Datasets](https://github.com/huggingface/datasets) library, covering data loading, processing, and manipulation.

### ⚡ **peft/** & **peft_docs/**
Examples using [Parameter-Efficient Fine-Tuning (PEFT)](https://github.com/huggingface/peft) techniques like LoRA and prompt tuning for efficient model training.

### ☁️ **sagemaker/**
30+ notebooks demonstrating how to use Hugging Face models with [Amazon SageMaker](https://aws.amazon.com/sagemaker/), including:
- Training and deployment examples
- Distributed training
- Inference optimization
- Integration with SageMaker features

### 💡 **examples/**
Standalone example notebooks covering various tasks:
- Text classification
- Named entity recognition
- Question answering
- Image classification
- Audio processing
- Time series
- And more!

### 🤖 **lerobot/**
Notebooks for robot learning using the [LeRobot](https://github.com/huggingface/lerobot) framework.

### 📦 **Other directories:**
- **huggingface_hub/** - Using the Hugging Face Hub API
- **setfit_doc/** - Few-shot learning with SetFit
- **smolagents_doc/** - AI agents documentation
- **safetensors_doc/** - Safe tensor serialization
- **longform-qa/** - Long-form question answering

## 🚀 Getting Started

### Prerequisites

1. **Python 3.8+** installed on your system
2. **Jupyter Notebook or JupyterLab** to run the notebooks
3. **Git** to clone the repository

### Installation

1. **Clone this repository:**
```bash
git clone https://github.com/LetsVenture2021/training-notebooks.git
cd training-notebooks
```

2. **Set up a virtual environment (recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Jupyter:**
```bash
pip install jupyter notebook
# or for JupyterLab
pip install jupyterlab
```

4. **Install required libraries:**

   Each notebook typically includes installation cells at the beginning. However, you can install common libraries upfront:

```bash
# Core libraries
pip install transformers datasets accelerate

# For diffusion models
pip install diffusers

# For PEFT
pip install peft

# For training on SageMaker
pip install sagemaker

# For specific examples, check requirements.txt files in subdirectories
```

### Running the Notebooks

1. **Start Jupyter:**
```bash
jupyter notebook
# or
jupyter lab
```

2. **Navigate to a notebook** in the web interface that opens

3. **Run the notebook cells** sequentially using Shift+Enter

4. **Follow any specific setup instructions** mentioned in individual notebooks

## 📝 Usage Examples

### Example 1: Text Classification
Navigate to `examples/text_classification.ipynb` to learn how to fine-tune a model for text classification tasks.

### Example 2: Stable Diffusion
Check out `diffusers/stable_diffusion.ipynb` for generating images from text prompts.

### Example 3: SageMaker Training
Explore `sagemaker/01_getting_started_pytorch/` for deploying models on AWS SageMaker.

### Example 4: PEFT Fine-tuning
See `peft/` for parameter-efficient fine-tuning examples using LoRA and other techniques.

## 🤝 Contributing

Contributions are welcome! However, please note:

- **course/** and **transformers_doc/** directories are auto-generated. To fix issues:
  - For `course/`: Open a PR in the [course repository](https://github.com/huggingface/course)
  - For `transformers_doc/`: Open a PR in the [transformers repository](https://github.com/huggingface/transformers)

- For other notebooks, feel free to open a pull request with improvements!

See the [pull request template](.github/pull_request_template.md) for more details.

## 📚 Additional Resources

- [Hugging Face Documentation](https://huggingface.co/docs)
- [Hugging Face Course](https://huggingface.co/course)
- [Hugging Face Forum](https://discuss.huggingface.co/)
- [Hugging Face Discord](https://discord.gg/hugging-face)
- [Model Hub](https://huggingface.co/models)
- [Datasets Hub](https://huggingface.co/datasets)

## 🔧 Troubleshooting

### Common Issues

1. **Module not found errors:** Install the required library using `pip install <library-name>`
2. **CUDA/GPU issues:** Ensure you have the correct PyTorch version for your CUDA version
3. **Memory errors:** Try reducing batch sizes or using gradient accumulation
4. **SageMaker notebooks:** Ensure you have AWS credentials configured and proper IAM permissions

### Getting Help

- Check the [Hugging Face Forum](https://discuss.huggingface.co/)
- Open an issue in the relevant library's GitHub repository
- Join the [Hugging Face Discord](https://discord.gg/hugging-face)

## 📄 License

This repository is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

These notebooks are maintained by the Hugging Face community and demonstrate the capabilities of various Hugging Face libraries. Special thanks to all contributors!

---

**Happy Learning! 🎉**
