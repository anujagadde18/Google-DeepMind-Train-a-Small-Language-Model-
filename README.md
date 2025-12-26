# Character-Level Language Modeling for Arabic

[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-Educational-lightgrey)](LICENSE)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](gdm_challenge_lab.ipynb)

---

## Table of Contents
1. [Abstract](#abstract)
2. [Overview](#overview)
3. [Repository Contents](#repository-contents)
4. [Methodology](#methodology)
   - [Character-Level Tokenizer](#character-level-tokenizer)
   - [N-Gram Text Generator](#n-gram-text-generator)
   - [Data Preparation for Transformer Training](#data-preparation-for-transformer-training)
5. [Skills and Concepts](#skills-and-concepts)
6. [Experimental Environment](#experimental-environment)
7. [Figures and Visualizations](#figures-and-visualizations)
8. [Notes](#notes)
9. [Related Blog Post](#related-blog-post)
10. [License](#license)

---

## Abstract
This repository documents work completed as part of the **Google DeepMind AI Foundations Challenge Lab**, aiming to build the core components of a **character-level language model for Arabic text**. The project emphasizes independent problem-solving and understanding of fundamental concepts in language modeling, particularly for **morphologically rich languages** like Arabic.

---

## Overview
The objective of this project is to implement **foundational tools** necessary for training a character-level language model using **short Arabic children’s stories**. The focus is on:

- Data preprocessing and preparation  
- Character-level tokenization  
- Sequence modeling for effective language representation  

The work demonstrates methods for text segmentation, tokenization, and sequence alignment, which are critical to **stable model training**.

---

## Repository Contents
| File | Description |
|------|-------------|
| `gdm_challenge_lab.ipynb` | Jupyter notebook containing all implementations for the challenge lab tasks |

---

## Methodology

### Character-Level Tokenizer
- Splits Arabic text into individual character tokens  
- Reconstructs text from tokens **without loss**  
- Defines the **vocabulary and token space** for downstream models  

---

### N-Gram Text Generator
- Implements a **character-level n-gram model** as a baseline  
- Supports **greedy** and **random sampling**  
- Generates text **one character at a time**  
- Serves as a reference for evaluating more complex models  

---

### Data Preparation for Transformer Training
- Encodes text into token IDs  
- Segments long sequences into fixed-length chunks  
- Constructs **aligned input–target pairs** suitable for transformer-based language models  

Correct sequence segmentation and alignment is central to **stable and reproducible model training**.

---

## Skills and Concepts
- Character-level tokenization  
- N-gram language modeling  
- Text generation logic  
- Sequence segmentation and padding  
- Dataset preparation for transformer-based models  
- Debugging in **constrained, non-guided environments**

---

## Experimental Environment
- **Google Cloud / Vertex AI Colab** provided by the challenge lab  
- Compatible with **local Python 3.x + Jupyter Notebook environments**


