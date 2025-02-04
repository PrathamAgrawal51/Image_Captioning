# 🖼️ Image Captioning using CNN & Transformer  

A deep learning-based **Image Captioning Model** that generates descriptive captions for images using **Convolutional Neural Networks (CNNs) for feature extraction** and **Transformer models for sequence generation**.  

## 📌 Project Overview  

This research project aims to improve image captioning by leveraging **CNNs for visual feature extraction** and **Transformer-based models for generating captions**. The model is trained on the **Flickr8k dataset**, which consists of **8,092 images**, each annotated with **five descriptive captions**.  

## 🚀 Features  

- 📸 **Image Feature Extraction** – Uses a CNN Model to extract visual embeddings.  
- 🔡 **Caption Generation** – Utilizes a **Transformer model** to generate coherent and meaningful captions.  

## 🏗️ Model Architecture  

### 1️⃣ **Image Feature Extraction (CNN)**  
- A CNN Model extracts **high-level image features**.  
- The last fully connected layer is removed to obtain feature vectors.  

### 2️⃣ **Caption Generation (Transformer)**  
- A **Transformer-based decoder** processes the extracted image features.  
- Uses **self-attention** to capture contextual dependencies.  
- Outputs a sequence of words forming a meaningful caption.  

## 📊 Dataset  

- **Flickr8k Dataset** 🖼️  
  - **8,092 images** in JPEG format.  
  - Each image has **five different textual descriptions**.  
  - Used for training, validation, and testing.  

## 🔧 Installation & Usage  

1️⃣ **Clone the repository:**  
```sh
git clone https://github.com/PrathamAgrawal51/Image_Captioning.git
```
2️⃣ **Run the model:**
- Download the Flickr8k dataset and pretrained weights.
- Open and execute the image_captioning_transformer.ipynb notebook.
- Upload an image to generate captions!

## 🎯 Future Improvements
- ✅ Experiment with Vision Transformers (ViTs) for better feature extraction.
- ✅ Fine-tune on larger datasets (MS-COCO) for improved generalization.
- ✅ Enhance caption fluency using RL-based optimization (CIDEr / BLEU scores).

## 🤝 Contributing
Contributions are welcome! If you'd like to improve the model, feel free to open an issue or submit a pull request.
