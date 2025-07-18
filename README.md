# 🛍️ Multimodal E-commerce AI Agent

This repository contains Jupyter notebooks for building a multimodal AI agent that enhances the e-commerce experience using a combination of computer vision and natural language processing (NLP).  
The agent is designed to handle:
- 📷 Image-based product classification
- 🔍 Text-based product search
- 📝 Summarization of product data

All these tasks are integrated into a complete AI pipeline.

---

## 🔧 Features

- 🖼️ **Image Classifier**  
  Classifies product images into categories using deep learning (CNN-based models).

- 🔍 **Product Search**  
  Enables product search using NLP techniques on product descriptions and titles.

- ✍️ **NLP Summarizer**  
  Summarizes long product descriptions to improve readability and display.

- 🔄 **Full Pipeline**  
  Combines all the components into an end-to-end multimodal AI system.

---

## 📁 Repository Structure

| File                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `1_image_classifier.ipynb`  | Train and evaluate an image classification model for product categories.   |
| `2_product_search.ipynb`    | Implement semantic search using vector embeddings (e.g., sentence transformers). |
| `3_nlp_summarizer.ipynb`    | Generate summaries of product descriptions using transformer-based models. |
| `4_full_pipeline.ipynb`     | Combine image classification, search, and summarization into a unified system. |
| `.gitignore`                | Git ignore rules for files and directories.                               |
| `README.md`                 | This project overview and usage guide.                                    |

---

## 🧰 Requirements

- Python 3.8+
- Jupyter Notebook / JupyterLab

### 📦 Libraries

```bash
torch
transformers
scikit-learn
sentence-transformers
opencv-python
pandas
numpy
matplotlib
