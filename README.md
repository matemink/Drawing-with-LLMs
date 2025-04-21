# 🖌️ Drawing with LLMs: SVG Generation from Text Prompts

This repository contains the `drawin_with_llms.ipynb` notebook, which implements a rule-based model for generating Scalable Vector Graphics (SVG) code from natural language prompts. The project is built for the Kaggle competition focused on converting text into SVG images using the Kaggle Packages framework.

## 📘 Competition Overview

The goal of the competition is to build reusable, transparent models that convert textual image descriptions into executable SVG code. Submissions are evaluated on their ability to reason about abstract prompts and produce accurate vector graphics using a `Model` class with a `predict()` function.

## 📄 Notebook Summary

The notebook defines a `Model` class that follows the Kaggle Packages interface. Its `predict(prompt: str) -> str` method returns SVG code based on the input prompt.

## 🧩 Dependencies

This project requires the following key libraries:

- 🐍 **Python 3**: The core programming language.
- 🔧 **cairosvg**: Converts SVG files to formats like PNG or PDF.
- 🤖 **torch**: Deep learning framework for model inference.
- 📦 **transformers**: Hugging Face library for working with transformer-based models like **Gemma3**.
- 🧠 **Gemma3**: Model from the `transformers.models.gemma3` library for causal language modeling and conditional generation.
