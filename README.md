# Automatic Bangla Image Captioning Based on Transformer Model

> Official implementation of the paper:  
> **"Automatic Bangla Image Captioning Based on Transformer Model in Deep Learning"**  
> Published in *International Journal of Advanced Computer Science and Applications (IJACSA), Dec 2023*  
> [📄 Read Paper](http://dx.doi.org/10.14569/IJACSA.2023.01411113)

---

## 📌 Overview
This project implements a **Transformer-based image captioning model** for the Bangla language, combining **Computer Vision** and **Natural Language Processing (NLP)** techniques. It focuses on generating accurate and contextually relevant captions for Bangla images using deep learning.

**Key highlights:**
- **Encoder-Decoder Architecture**: CNN-based encoder for feature extraction and Transformer-based decoder for sequence generation.  
- **Pre-trained Feature Extractors**: ResNet50, InceptionV3, and VGG16 for robust image representation.  
- **Dataset**: Uses the **BAN-Cap dataset**, containing 8,091 images and 40,455 Bangla captions.  
- **Performance Metrics**: Evaluated with BLEU, METEOR, ROUGE, and CIDEr.  
- **Contribution**: Proposes a transformer-based model for Bangla image captioning, showing improved accuracy over traditional models.

---

## 🛠 Installation

```bash
git clone https://github.com/<username>/bangla-image-captioning-transformer.git
cd bangla-image-captioning-transformer
pip install -r requirements.txt
