# 🧠 Multimodal Streamlit App — Text ↔ Image (Local + Hugging Face)

A lightweight, **low-VRAM** multimodal AI app built with **Streamlit**, **Hugging Face Diffusers**, and **Ollama’s LLaVA** model.  
Generate **images from text** (Stable Diffusion Turbo) and **describe images** (LLaVA) — all locally, GPU-optimized, and secure. 🚀

---

## ⚙️ Features

🔹 **Text → Image:** Uses `stabilityai/sd-turbo` from Hugging Face.  
🔹 **Image → Text:** Powered by Ollama’s `llava:latest` model.  
🔹 **Low VRAM Support:** Works with GPUs like GTX 1650 (uses float32 and CPU offload).  
🔹 **Local + Secure:** Keeps API keys in `.streamlit/secrets.toml`, not in code.  
🔹 **Streamlit UI:** Simple, interactive two-tab interface.

---

## Configure Hugging Face Token
.streamlit/secrets.toml
[hf]
token = "hf_your_actual_token_here"



## 🧩 Requirements

- Python **3.10** or higher  
- GPU with CUDA (recommended)  
- [Ollama](https://ollama.com/download) installed and `llava` model pulled  
- Hugging Face account + access token  
- Git

---

## 📦 Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
