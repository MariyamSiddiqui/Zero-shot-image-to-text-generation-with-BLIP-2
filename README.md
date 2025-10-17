# 🧠 Zero-Shot Image-to-Text with BLIP-2 (Flan-T5)

This project demonstrates **zero-shot image-to-text generation** using the `Salesforce/blip2-flan-t5-xl` model from Hugging Face Transformers.  
BLIP-2 combines a vision encoder with a large language model, enabling **image captioning**, **visual question answering**, and **context-aware dialogue** — all without fine-tuning.

---

## 🚀 Features

- 🖼️ **Zero-shot image captioning** — describe any image without a prompt  
- 💬 **Prompted captioning** — guide generation with partial text  
- ❓ **Visual question answering (VQA)** — ask questions about the image  
- 🤝 **Chat-style interaction** — multi-turn reasoning using visual context  
- ⚡ GPU acceleration and half-precision (float16) for faster inference

---

## 📦 Requirements

Install dependencies:

```bash
pip install -U transformers accelerate torch pillow requests
