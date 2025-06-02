# Med-VQA: Multimodal Medical Visual Question Answering

A research project exploring **Medical Visual Question Answering (Med-VQA)** using **multimodal Retrieval-Augmented Generation (RAG)** and advanced prompting strategies for enhanced accuracy and explainability.

## 🧠 Overview
This project builds a system to answer medical questions based on input images (e.g., X-rays, MRIs) by integrating both **textual and visual evidence**. It leverages:
- Prompting techniques: Few-Shot, Chain-of-Thought (CoT), Tree-of-Thought (ToT)
- Retrieval-Augmented Generation using PubMedQA, SLAKE, and PMC-VQA
- Lightweight fine-tuning (LoRA) of LLaVA-Med

## 📊 Results
- **Prompting Recall**: Up to 77% (CoT, ToT)
- **Fine-tuned LLaVA-Med Accuracy**: 54.27%
- **RAG Enhanced Recall**: 71.83%

## 📁 Repository Structure
Med-VQA-Project/
├── code/ # Model training, RAG, retrieval modules
├── reports/ # Final project and proposal PDFs
├── README.md # Project overview and instructions


## 📚 Datasets Used
- **PMC-VQA** – 227k image-question pairs from PubMed Central
- **SLAKE** – Visual dataset with 14k QA pairs
- **PubMedQA** – Biomedical text QA dataset for retrieval context

## 🛠 Technologies
- Python, PyTorch, FAISS
- CLIP, MiniLM, GPT-4 API, LLaVA-Med, LoRA

## 🚀 Features
- Zero-shot and Few-shot image QA
- Visual + text-based retrieval
- Step-by-step answer justification (explainability)
- LoRA-tuned lightweight vision-language model

## 📄 License
This project is for academic use only.
