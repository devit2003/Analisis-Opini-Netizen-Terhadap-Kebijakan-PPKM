# Analisis Opini Netizen Terhadap Kebijakan PPKM Menggunakan IBM Granite

## Project Overview

Proyek ini bertujuan untuk menganalisis opini publik mengenai kebijakan Pemberlakuan Pembatasan Kegiatan Masyarakat (PPKM) di Indonesia dengan menggunakan model Large Language Model (LLM) IBM Granite. Dengan bantuan AI, proyek ini mengklasifikasikan opini netizen menjadi Agree, Neutral, atau Disagree dan menghasilkan ringkasan singkat dari setiap opini. Proses ini membantu mendapatkan insight yang bermakna untuk pengambilan keputusan kebijakan pemerintah.

## Raw Dataset Link

- INA Tweets PPKM — Kaggle
- https://www.kaggle.com/datasets/anggapurnama/twitter-dataset-ppkm

## Insight & Findings

- Mayoritas opini netizen cenderung Tidak Setuju terhadap kebijakan PPKM.
- Topik utama yang sering muncul dalam opini negatif adalah:
  - Dampak ekonomi yang negatif.
  - Kurangnya sosialisasi dan informasi terkait kebijakan.
- Wordcloud dan pie chart menunjukkan bahwa kata-kata seperti "kerja", "bantuan", dan "lockdown" mendominasi opini.

## AI Support Explanation

- **Model Digunakan:** IBM Granite 3.3-8B Instruct melalui Replicate API.
- **Fungsi AI:**
  - Klasifikasi opini menjadi Agree, Neutral, atau Disagree.
  - Summarization opini menjadi kalimat ringkas.
  - Menghasilkan insight dan rekomendasi berdasarkan dataset.
- **Alasan Penggunaan:**
  - Model LLM ini mampu memahami instruksi kompleks dan menghasilkan output yang relevan untuk analisis opini dan insight bisnis.

---

> Dibangun menggunakan Google Colab, Gradio, Pandas, Matplotlib, Langchain Community, dan Replicate API.
