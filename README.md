# Phytoscan
ML based project on detecting disease of plant and diagnosing it.
# 🌿 Phytoscan: AI-Powered Plant Disease Detection and Assistant

Phytoscan is an intelligent plant disease detection system powered by deep learning and generative AI. It uses pre-trained models and an interactive chat interface to identify diseases in plant leaves and offer helpful insights to farmers and researchers.

---

## 🚀 Features

- 📦 Downloads a plant disease dataset from Kaggle
- 🧠 Loads a pre-trained Keras model for image-based disease classification
- 🧑‍🌾 Uses Google's Generative AI SDK (`google-genai`) to generate natural language responses for detected diseases
- 💬 Provides a simple Gradio-powered chatbot interface for user interaction

---

## 🧪 Dependencies

Make sure the following packages are installed:

```bash
pip install httpx==0.13.3
pip uninstall -qy jupyterlab jupyterlab-lsp
pip install -qU gradio
pip install -qU 'google-genai==1.7.0'

