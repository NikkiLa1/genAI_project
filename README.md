# Self-RAG: Evaluating Self-Reflective Retrieval-Augmented Generation on Biomedical Question Answering
**Presented by:** Nikki La, Dec 4

## Project Overview

This project compares a Self-Reflective Retrieval-Augmented Generation (Self-RAG) model with a baseline RAG pipeline on the BioASQ Task B biomedical question-answering dataset. The goal is to evaluate whether integrating a self-reflection loop improves factual accuracy and reduces hallucinations in scientific Q&A.

## Problem Statement

Large Language Models (LLMs) frequently produce confident but incorrect statements, especially in biomedical contexts where precision is critical. This project assesses whether integrating a self-reflection loop into RAG enhances factual grounding in biomedical question answering.

## Approach

1. **Baseline RAG**: Standard retrieval-augmented generation using FAISS for document retrieval and an LLM for answer generation
2. **Self-RAG**: Extended RAG with a reflection stage where the model critiques and revises its initial answer using retrieved evidence
3. **Evaluation**: Compare both systems on BioASQ Task B using quantitative metrics (Exact Match, ROUGE) and qualitative analysis
