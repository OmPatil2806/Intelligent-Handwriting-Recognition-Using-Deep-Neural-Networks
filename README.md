# 📝 Handwriting Recognition Using Deep Learning

## Project Overview
Deep learning-based handwriting recognition using **CRNN (CNN + BiLSTM)** and **ResNet-CTC** models. This project automatically converts handwritten words into digital text, evaluates accuracy, visualizes predictions, and analyzes character-level confusion patterns.

This project demonstrates the power of deep neural networks in recognizing complex handwritten sequences and provides a strong baseline for real-world handwriting transcription applications.

---

##  Problem Statement
Manual transcription of handwritten documents is time-consuming, error-prone, and expensive. Traditional OCR struggles with handwritten text due to variations in style, spacing, and alignment. This project builds an automated system capable of recognizing handwritten words efficiently and accurately.

---

##  Business Problem
Organizations like banks, healthcare providers, educational institutions, and government offices deal with large volumes of handwritten forms and applications. Automating handwriting recognition reduces operational cost, minimizes errors, and speeds up processing, improving overall productivity.

---

##  Model Architecture

### 1. CRNN (CNN + BiLSTM + CTC)
- CNN layers for feature extraction  
- Bidirectional LSTM for sequence modeling  
- Dense layer → CTC loss for training sequence-to-sequence recognition  

### 2. ResNet-CTC (CNN-only baseline)
- Residual CNN blocks for feature extraction  
- Dense layer → CTC loss for sequence prediction  
- Faster training with fewer parameters  

---

##  Training Setup
- **Optimizer:** Adam  
- **Loss:** CTC (Connectionist Temporal Classification)  
- **Batch size:** 16–64  
- **Epochs:** 10–50  
- **Input image size:** 128x32 grayscale  

---

##  Evaluation Metrics
- Accuracy (character-level and word-level)  
- Precision, Recall, F1-score  
- Confusion Matrix visualization  
- Sample predictions for qualitative assessment  

---

##  Results
- CRNN provides strong recognition for longer words and complex sequences.  
- ResNet-CTC trains faster and is suitable for lightweight applications.  
- Common misclassifications occur for similar characters (e.g., ‘0’ vs ‘O’, ‘I’ vs ‘l’).  

---

##  Visualizations
- Sample predictions on test images  
- Character-level confusion matrices for error analysis  

---

##  Technologies & Tools

| Category          | Tools & Libraries                |
|------------------|---------------------------------|
| Programming       | Python                          |
| Deep Learning     | TensorFlow, Keras               |
| Data Processing   | NumPy, Pandas                   |
| Visualization     | Matplotlib, Seaborn             |
| Model Evaluation  | scikit-learn                    |
| File Handling     | OS, tarfile, zipfile            |

---

##  Future Work
- Integrate Transformer-based OCR for improved sequence learning  
- Add data augmentation for better handwriting style generalization  
- Extend recognition to line-level or paragraph-level text  
- Deploy as a web/mobile application for real-time handwriting transcription  

---

## 🙌 Contributions

Contributions are welcome!  
Feel free to open issues, fork the repo, and submit pull requests.

---

## 👤 Author

**Om Patil**  
📧 Data Science & Machine Learning Enthusiast  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
