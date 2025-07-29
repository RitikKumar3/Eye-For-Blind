# Capstone Project : Eye For Blind
# 🖼️ Image Captioning with Speech Output
- In this project, we build a **CNN-RNN model with Attention Mechanism** to generate descriptive captions for images and convert them into **speech output**. This solution is designed to assist visually impaired individuals in understanding images through audio descriptions.

---

## Problem Solving Methodology
> The project accomplishes the following tasks:

- **Data Understanding & Preprocessing**  
> Loaded and analyzed the Flickr8K dataset. Images were resized, features extracted using a CNN encoder, and captions were tokenized, cleaned, and padded to prepare them for model training.

- **Model Architecture**  
> Implemented an **Encoder-Decoder architecture with Attention Mechanism**:  
> - Encoder: Pre-trained CNN (InceptionV3) for image feature extraction.  
> - Decoder: LSTM-based network to generate captions sequentially.  
> - Attention Layer: Helps the model focus on important parts of the image while generating captions.

- **Caption Generation & Evaluation**  
> Used **Greedy Search** to generate captions and evaluated the performance using **BLEU Score**.

- **Text-to-Speech Conversion**  
> Converted the generated captions into **speech output** using Python text-to-speech libraries (`gTTS` / `pyttsx3`).

---

## Technologies Used
- **Python 3**, Jupyter Notebook

---

## Libraries Used
- TensorFlow, Keras, Numpy, Pandas, Matplotlib, Seaborn  
- NLTK, Pillow (PIL), OpenCV  
- gTTS / pyttsx3 for speech synthesis  

---

## Contributor
* **Ritik Kumar** ([LinkedIn Profile](https://www.linkedin.com/in/ritik-kumar-717313221))  

- Feel free to contact me for collaboration or improvements.  

---

## Future Work
- Implement **Beam Search** for better caption generation accuracy.  
- Explore **Transformer-based models** for enhanced results.  
- Deploy as a **real-time web or mobile application** for accessibility use cases.  
