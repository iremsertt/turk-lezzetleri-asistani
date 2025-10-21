[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iremsert/turk-lezzetleri-asistani/blob/main/colab_setup.ipynb)

# 🍲 Türk Lezzetleri Asistanı – RAG Tabanlı Yemek Tarifi Chatbot

Bu proje, Türk yemek tariflerini **sor-yanıt** ve **malzemeye göre öneri** modlarında sunan  
RAG (Retrieval-Augmented Generation) tabanlı bir yapay zekâ uygulamasıdır.  
Model altyapısı `Phi-3-mini-4k-instruct` (üretim) ve `MiniLM` (embedding) kullanır.

---

## 🎯 Proje Özeti
- **Amaç:** Türkçe yemek tariflerini doğal dilde sorgulayıp akıllı yanıt üretmek  
- **Teknoloji:** RAG (Retrieval + Generation), FAISS, Sentence Transformers, Gradio  
- **Veri Kümesi:** [mertbozkurt/turkish-recipe](https://huggingface.co/datasets/mertbozkurt/turkish-recipe)

---

## 🌿 Özellikler

- **🔍 Tarif Sor:** “Karnıyarık nasıl yapılır?”
- **🥦 Malzemeye Göre Öneri:** “tavuk, et, sarımsak” gibi girdilerden tarif önerir
- **LLM:** Phi-3-mini (Microsoft)
- **Embedding:** MiniLM
- **Arayüz:** Gradio

---
## ⚙️ Kurulum
```bash
pip install -r requirements.txt
python app.py

