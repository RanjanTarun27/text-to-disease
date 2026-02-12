# text-to-disease
This repository contains a high-performance Natural Language Processing (NLP) pipeline for classifying diseases based on short symptom descriptions. By leveraging a BERT-base-cased architecture with a custom Self-Attention mechanism, the model achieves 97% accuracy on the test set while providing interpretable clinical insights.

🚀 Key Features
BERT Backbone: Utilizes bert-base-cased for superior handling of medical terminology and case-sensitive acronyms.

Self-Attention Head: A custom attention layer that weighs the clinical significance of specific symptom keywords (e.g., "crushing" in "crushing chest pain").

Multi-Sample Dropout: Implements 5-sample dropout layers to ensure model stability and prevent overfitting.

Explainable AI (XAI): Integrated scoring to show which tokens (symptoms) most influenced the model's diagnosis.

Interactive UI: Built-in Gradio web interface for real-time inference and public sharing.


Tech Stack

Language: Python

Deep Learning: PyTorch

Transformers: Hugging Face

Interface: Gradio

Visualization: Matplotlib

👨‍🔬 Professional Application
This project is designed as a Clinical Decision Support System (CDSS). It demonstrates how Large Language Models can be fine-tuned for high-stakes domains where interpretability and high precision are non-negotiable.

Clinical Disease Classifier (BERT + Self-Attention)

Developed an NLP model using BERT-base-cased to classify 10+ diseases from symptom text with 97% accuracy.

Engineered a custom Self-Attention mechanism to identify and weigh critical clinical indicators within raw text.

Implemented Multi-Sample Dropout and Gradio for a robust, production-ready web deployment.

Enabled Explainable AI by visualizing attention weights to provide transparent diagnostic reasoning.
