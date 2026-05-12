<div align="center">
  <img src="_img\llms.jpg" alt="Applied LLM Development Banner" width="100%">
  
  # 🧠 Applied LLM Development & Deep Learning

  <p align="center">
    <b>A complete, end-to-end curriculum covering deep learning fundamentals through LLM fine-tuning, RAG, and production deployment.</b>
  </p>
  <br/>
</div>

## 📖 Overview

Welcome to the **Applied LLM Development** repository! This project contains a comprehensive course structure designed to take you from the basics of PyTorch to operationalizing state-of-the-art Large Language Models (LLMs) in production. 

All slide content from the original course has been transformed into interactive, self-contained **Jupyter Notebooks**. Each notebook combines rich markdown explanations with fully runnable code, giving you a hands-on learning experience.

Whether you're a data scientist, software engineer, or AI enthusiast, this curriculum provides the practical skills necessary to build, fine-tune, and deploy LLM applications.

---

## ✨ Key Features

- **Interactive Learning**: Theory and practice combined in Jupyter Notebooks.
- **Progressive Curriculum**: From basic PyTorch tensors to advanced Parameter-Efficient Fine-Tuning (PEFT) and LLMOps.
- **Real-World Projects**: Sentiment analysis, custom LLM fine-tuning, and RAG pipelines.
- **Modern Tech Stack**: PyTorch, Hugging Face Transformers, PEFT, QLoRA, and LangChain/LlamaIndex concepts.

---

## 🎯 What You Will Learn

* **Deep Learning Fundamentals**: Build neural networks from scratch using PyTorch.
* **Computer Vision & NLP**: Work with CNNs, RNNs, LSTMs, and sequence models.
* **Transformer Architecture**: Understand self-attention, positional encoding, and BERT.
* **LLM Fine-Tuning**: Master techniques like LoRA and QLoRA for efficient model adaptation.
* **LLMOps**: Deploy models robustly, track performance, and implement guardrails in production environments.

---

## 📂 Repository Structure & Curriculum

The repository is structured sequentially. We recommend progressing from Module 01 through Module 07.

<details open>
<summary><b>Click to expand the full directory tree</b></summary>

```text
Applied-LLM-Development/
│
├── 01-Deep-Learning-with-PyTorch-Introduction/
│   ├── notebooks/ (Intro to Deep Learning, Forward Pass, Activations, Data)
│   └── datasets/
│
├── 02-Deep-Learning-with-PyTorch-Intermediate/
│   ├── notebooks/ (PyTorch OOP, CNNs, RNNs/LSTMs, Multi-Input Models)
│   └── datasets/
│
├── 03-Deep-Learning-for-Text-with-PyTorch/
│   ├── notebooks/ (Text Preprocessing, Classification, Generation, BERT)
│   └── datasets/
│
├── 04-Introduction-to-LLMs-in-Python/
│   └── notebooks/ (Attention Mechanisms, Hugging Face APIs, Evaluation)
│
├── 05-PROJECT-Analyzing-Car-Reviews-with-LLMs/
│   └── Project_Analyzing_Car_Reviews_with_LLMs.ipynb
│
├── 06-PROJECT-Fine-Tuning-Your-Own-Llama2-Model/
│   └── Project_Fine_Tuning_LLaMA2.ipynb
│
├── 07-PROJECT-LLMOps-Operationalizing-LLMs/
│   └── Project_LLMOps_Guide.ipynb
│
├── Pytorch-cheatsheet/
│   └── (Quick reference guides and cheat sheets for PyTorch)
│
└── _img/
    └── (Assets and banners)
```
</details>

---

## 📚 Module Descriptions

### 🟢 Fundamentals
* **Module 01: Deep Learning with PyTorch - Introduction**  
  *Topics:* Tensors, Forward Passes, Training Loops, Binary & Multiclass Classification, Activation Functions (Sigmoid, ReLU), Custom Datasets, and DataLoaders.
* **Module 02: Deep Learning with PyTorch - Intermediate**  
  *Topics:* OOP in PyTorch, Image Handling, CNN architectures, Sequential Data, RNNs, LSTMs, Time Series Splitting, and Multi-input Models.
* **Module 03: Deep Learning for Text with PyTorch**  
  *Topics:* NLP Pipelines, Tokenization, Word Embeddings, Padding, Character-level Text Generation, Transfer Learning, and BERT Fine-tuning.

### 🔵 Advanced & Applied LLMs
* **Module 04: Introduction to LLMs in Python**  
  *Topics:* Attention Mechanisms, Positional Encoding, Self-Attention, Hugging Face `pipeline()` API, AutoModel, AutoTokenizer, and Evaluation Metrics (Accuracy, F1, BLEU, ROUGE, Perplexity).
* **Module 05: Project - Analyzing Car Reviews with LLMs**  
  *Topics:* A full end-to-end pipeline covering loading data, sentiment analysis, summarization, visualization, and model evaluation.
* **Module 06: Project - Fine-Tuning Your Own LLaMA Model**  
  *Topics:* Parameter-Efficient Fine-Tuning (PEFT), QLoRA, LoRA adapters, `llama.cpp` inference, and transitioning to modern architectures (LLaMA 2 / LLaMA 3).
* **Module 07: Project - LLMOps & Operationalizing LLMs**  
  *Topics:* Prompt versioning, RAG (Retrieval-Augmented Generation) pipelines, performance monitoring, guardrails, and best practices for production deployments.

---

## 🛠️ Prerequisites

* Basic understanding of Python programming.
* Familiarity with fundamental math (linear algebra and calculus) is helpful but not strictly required.
* A machine with a GPU (or access to Google Colab/Kaggle) is highly recommended for Modules 04–07.

---

## ⚙️ Setup & Installation

To run the notebooks locally, we recommend using a virtual environment (such as `conda` or `venv`). 

```bash
# 1. Clone this repository
git clone https://github.com/mohd-faizy/Applied-LLM-Development.git
cd Applied-LLM-Development

# 2. Create a virtual environment (Optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install core dependencies
pip install torch torchvision torchaudio
pip install transformers datasets evaluate
pip install peft trl bitsandbytes accelerate
pip install scikit-learn pandas matplotlib nltk torchtext jupyterlab
```

---

## 🚀 Getting Started

1. Open Jupyter Lab or Jupyter Notebook:
   ```bash
   jupyter lab
   ```
2. Navigate to `01-Deep-Learning-with-PyTorch-Introduction/notebooks/Chapter_01_Introduction_to_Deep_Learning.ipynb`.
3. Work through the modules chronologically. Each notebook is self-contained with comprehensive markdown explanations and executable Python cells.

---

## 📎 Credits

* Course content based on the *Developing Large Language Models* curriculum.
* Notebooks generated and thoughtfully expanded from original course slides to provide a fully interactive learning environment.

---

## Contributing and Support

Contributions are welcome. Please open an issue before submitting major changes.

If this repository helps you, consider giving it a star so other learners can discover it.

<div align="center">
  <br/>
  <p><b>Connect with me</b></p>
  <a href="https://twitter.com/F4izy">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="https://www.linkedin.com/in/mohd-faizy/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/mohd-faizy">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</div>

---

## License

Distributed under the MIT License. See [`LICENSE`](LICENSE) for more information.
