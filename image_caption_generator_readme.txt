# 🖼️ Image Caption Generator (BLIP Transformer)

This project uses the **BLIP (Bootstrapping Language-Image Pretraining)** model to generate natural-language captions for uploaded images. Built using **Transformers** and **Gradio**.

---

## 🚀 Live Demo
🔗 [Try it on Hugging Face Spaces](https://huggingface.co/spaces/maheshc/image-caption-generator) *(replace with your actual link)*

---

## 📦 Features
- Upload any image and get a meaningful caption
- Based on BLIP pre-trained model from Hugging Face
- Fast, lightweight, and interactive UI using Gradio
- Supports a wide range of visual contexts (people, objects, scenes)

---

## 🧠 Concepts Learned
- Vision + Language models (multimodal AI)
- Hugging Face Transformers: BLIPProcessor, BLIPForConditionalGeneration
- Image preprocessing for captioning tasks
- Text decoding and cleanup
- Gradio interface building and deployment

---

## 🔁 Pipeline Flow
```text
1. User uploads an image
2. Image is preprocessed using BLIPProcessor
3. Model generates caption token IDs
4. Tokens decoded to natural-language caption
5. Caption shown via Gradio interface
```

---

## 💻 How to Run Locally
```bash
pip install -r requirements.txt
python app.py
```

---

## 📁 File Structure
```
├── app.py              # Main application file
├── requirements.txt    # Required Python libraries
```

---

## 👤 Author
Created by Mahesh C — Exploring GenAI, one image at a time 🤖

---

## 📝 License
This project is for educational use and is MIT-licensed.
