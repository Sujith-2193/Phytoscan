# Phytoscan


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
```

---

## 📥 Dataset and Model

The notebook fetches the following resources using `kagglehub`:

- **Dataset:** [vipoooool/new-plant-diseases-dataset](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
- **Model:** Pre-trained model

> Make sure you have access to Kaggle and have your API key set up before using `kagglehub`.

---

## 🧠 Powered by Google GenAI

The chatbot functionality uses the **Google Generative AI SDK**, allowing natural-language conversations about detected diseases. It provides insights, tips, and additional information.

---

## 🖼️ Interface

The project uses **Gradio** for a simple user interface:

- Upload a leaf image
- Get prediction results from the model
- Ask follow-up questions via chat (powered by GenAI)

---

## 🔒 Note on API Keys

To use the Google GenAI SDK:

```bash
export GOOGLE_API_KEY="your-key-here"
```

---

## 📚 How to Run

1. Clone the repo or upload the notebook to Colab/Jupyter
2. Ensure all dependencies are installed
3. Run each cell in sequence
4. Interact via the Gradio UI

---

## 📌 Credits

- [Kaggle Datasets and Models](https://kaggle.com)
- [Google Generative AI SDK](https://ai.google.dev/)
- [Gradio](https://www.gradio.app/)

---


