# qwen3-tts-oneshot-cloning

🎙️ **Voice Cloner (Powered by Qwen3-TTS)**

This repository contains a simple, easy-to-use Jupyter Notebook / Google Colab implementation for one-shot voice cloning using the `Qwen/Qwen3-TTS-12Hz-1.7B-Base` model. It features a beautifully simple Gradio interface that lets you clone any voice in seconds.

## ✨ Features
* **One-Shot Voice Cloning:** Clone a voice using just a 3-to-5 second audio clip.
* **Multilingual Support:** Generate cloned speech in English, Chinese, Japanese, Spanish, or French.
* **Interactive UI:** A fully functional Gradio web interface that runs directly inside your notebook.
* **Colab Ready:** Built-in checks and configurations to ensure smooth execution on Google Colab's T4 GPUs.

## 🚀 Getting Started

### Prerequisites
You need a machine with a **GPU** to run this model efficiently. If you are using Google Colab:
1. Go to the top menu and click `Runtime` > `Change runtime type`.
2. Under `Hardware accelerator`, select **T4 GPU**.
3. Click `Save`.

### Installation
The notebook automatically handles the installation of required dependencies. When you run the setup cell, it will install:
```bash
pip install -q -U qwen-tts gradio soundfile
