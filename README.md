# Gradio Applications for Generative AI  

This repository contains three AI-powered applications built using **Gradio**, a user-friendly framework for creating machine learning interfaces. The applications explore **Gradio Interface** and **Gradio Blocks** while leveraging pre-trained models from Hugging Face.  

## Applications  

### 1️⃣ Summarized Text and Named Entity Recognition (NER)  
- **Summarization Model:** [distilbart-cnn](https://huggingface.co/facebook/bart-large-cnn)  
- **NER Model:** [bert-base-NER](https://huggingface.co/dslim/bert-base-NER)  
- **Description:**  
  - Summarizes input text using a transformer-based model.  
  - Identifies and classifies named entities (e.g., people, organizations, locations) in the text.  

### 2️⃣ Image Captioning App  
- **Model Used:** [blip-image-captioning-base](https://huggingface.co/Salesforce/blip-image-captioning-base)  
- **Description:**  
  - Generates descriptive captions for uploaded images using BLIP (Bootstrapped Language-Image Pretraining).  

### 3️⃣ Image Generation App  
- **Model Used:** [stable-diffusion-xl-base-1.0](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)  
- **Description:**  
  - Generates images from text prompts using the **Stable Diffusion XL** model.  

## Implementation Details  
- Models were downloaded from **Hugging Face** using:  
  - `transformers` library for text-based applications.  
  - `diffusers` library for image generation.  
- Alternatively, the **Hugging Face Inference API** can be used for model execution without local downloads.  

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/kral-hacker/Exploring-Gradio-for-GenAI-Applications
   cd your-repo

2. Install dependencies:
   pip install -r requirements.txt


## Future Enhancements
Improve UI with advanced Gradio Blocks.
Support more summarization models and NER datasets.
Enhance image generation capabilities with fine-tuned models.

