# AI Engineering Portfolio

This repository is a curated **AI Engineering portfolio** showcasing hands-on projects in **machine learning, deep learning, and large language models (LLMs)**.

It is designed to demonstrate:
- Practical understanding of modern AI tools
- Clean, reproducible experimentation
- Engineering-oriented thinking (not just coursework)

> 📌 **Note**: Large datasets and trained models are intentionally excluded to follow GitHub best practices. All notebooks are fully reproducible.

---

## 🧠 Project Structure

ai-engineering-portfolio/
│
├── pytorch/
│ ├── cnn_fashion_mnist.ipynb
│ └── cnn_image_classifier.ipynb
│
├── transformers/
│ └── text_classification_transformers.ipynb
│
├── rag-langchain/
│ └── document_qa_rag.ipynb
│
├── llms/
│ └── prompt_engineering_basics.md
│
└── README.md

yaml
Copy code

---

## 🔥 Key Projects

### 1️⃣ PyTorch – Deep Learning Fundamentals
**Folder:** `pytorch/`

- Implemented **CNNs from scratch** using PyTorch
- Worked with image classification pipelines
- Focused on:
  - Model architecture design
  - Training loops
  - Evaluation metrics
  - Overfitting & generalization

📌 Datasets (Fashion-MNIST, CIFAR-10) are downloaded programmatically inside notebooks.

---

### 2️⃣ Transformers – Text Classification
**Folder:** `transformers/`

- Fine-tuned **DistilBERT** for text classification
- Used Hugging Face `Trainer` API
- Implemented:
  - Tokenization
  - Dataset preprocessing
  - Training & evaluation
  - Accuracy-based performance analysis

📌 Demonstrates real-world NLP workflow using production-grade libraries.

---

### 3️⃣ RAG (Retrieval-Augmented Generation)
**Folder:** `rag-langchain/`

- Built a **Document Question Answering system**
- Combined:
  - Document loaders
  - Embeddings
  - Vector search
  - LLM-based answer generation

📌 Focused on *LLM application architecture*, not just prompts.

---

### 4️⃣ LLMs – Prompt Engineering
**Folder:** `llms/`

- Practical notes on **prompt engineering fundamentals**
- Covers:
  - Prompt structure
  - Instruction clarity
  - Few-shot vs zero-shot prompting
  - Common pitfalls

📌 Written as an engineering reference, not theory notes.

---

## 🛠 Tech Stack

- **Languages:** Python
- **Frameworks:** PyTorch, Hugging Face Transformers
- **LLMs:** DistilBERT, OpenAI-compatible models
- **RAG:** LangChain
- **Tools:** Google Colab, Git, GitHub

---

## 🧪 Reproducibility

All notebooks:
- Download datasets programmatically
- Avoid committing large files
- Can be executed end-to-end in **Google Colab** or locally

---

## 🎯 Purpose of This Repository

This portfolio was built to:
- Prepare for **AI / ML / LLM internships**
- Demonstrate **practical engineering skills**
- Show ability to learn, debug, and ship working AI systems

It reflects **how I think and work**, not just what I studied.

---






