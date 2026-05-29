# 🧠 Deep Learning Lab — Practical File Index
### M.Tech | Semester II | Subject: Deep Learning Lab (DLL)

---

> **Student:** *Divyansh Sehgal*
> **Roll No:** *25901327*
> **Session:** 2025–26
> **Instructor:** Ms. Diksha Kumari

---

## 📋 Table of Contents

| # | Experiment Title | Topic Area | File |
|---|-----------------|------------|------|
| 01 | [Single Layer Perceptron using Optimizer](#01-single-layer-perceptron-using-optimizer) | Perceptron / Foundations | `1a.ipynb`, `1b.ipynb` |
| 02 | [Image Classification using Multilayer Perceptron](#02-image-classification-using-multilayer-perceptron) | MLP / Feedforward Networks | `2a.ipynb`, `2b.ipynb` |
| 03 | [Bounding Box Detection using CNN](#03-bounding-box-detection-using-cnn) | CNN / Localization | `3.ipynb` |
| 04 | [Object Detection using CNN](#04-object-detection-using-cnn) | CNN / Detection | `4.ipynb` |
| 05 | [Implementation of R-CNN and Faster R-CNN](#05-implementation-of-r-cnn-and-faster-r-cnn) | R-CNN / Region Proposals | `5.ipynb`, `5b.ipynb` |
| 06 | [YOLO Traffic Sign Implementation](#06-yolo-traffic-sign-implementation) | CNN / Object Detection | `6.ipynb` |
| 07 | [RNN-Based Sequence Modelling](#07-rnn-based-sequence-modelling) | RNN / Sequential Data | `7.ipynb` |
| 08 | [Emotion Recognition using ViT](#08-emotion-recognition-using-vit) | Multimodal / Transformers | `8.ipynb` |
| 09 | [Denoising & Dimensionality Reduction using Autoencoders](#09-denoising--dimensionality-reduction-using-autoencoders) | Autoencoders / Medical MNIST | *Pending* |
| 10 | [Stable Diffusion with Hugging Face](#10-stable-diffusion-with-hugging-face) | Generative AI / Diffusion | `10.ipynb` |

---



## 📁 Experiment Details

### 01. Single Layer Perceptron using Optimizer
**Concepts:** Perceptron model, weight updates, gradient descent, optimizers (SGD, Adam)  
**Dataset:** Custom / linearly separable data  
**Key Outcomes:** Understand the fundamental building block of neural networks and how optimizers affect convergence.

---

### 02. Image Classification using Multilayer Perceptron
**Concepts:** Fully connected layers, activation functions (ReLU, Sigmoid), backpropagation  
**Dataset:** Custom room images (Keras and TensorFlow implementations)  
**Key Outcomes:** Build and train an MLP from scratch for multi-class room image classification.

---

### 03. Bounding Box Detection using CNN
**Concepts:** CNN architecture, regression head, IoU metric  
**Dataset:** Custom dataset / Bounding box annotations  
**Key Outcomes:** Predict bounding box coordinates around objects using a convolutional backbone.

---

### 04. Object Detection using CNN
**Concepts:** CNN feature maps, classification + localization  
**Dataset:** Fashion MNIST  
**Key Outcomes:** Implement and understand the pipeline for detecting objects within images using CNNs.

---

### 05. Implementation of R-CNN and Faster R-CNN
**Concepts:** Region proposals, R-CNN, Faster R-CNN, ResNet50_FPN, MobileNet_V3_Large  
**Dataset:** PASCAL VOC 2012 / Standard benchmarks  
**Key Outcomes:** Complete implementation of R-CNN from scratch and performance comparison against Faster R-CNN architectures.

---

### 06. YOLO Traffic Sign Implementation
**Concepts:** Single-shot detection, grid-based prediction, YOLO  
**Dataset:** Traffic Signs Dataset  
**Key Outcomes:** Implement YOLO architecture specifically tailored for real-time traffic sign detection.

---

### 07. RNN-Based Sequence Modelling
**Concepts:** Recurrent Neural Networks, sequence processing  
**Dataset:** IMDB / Text sequence data  
**Key Outcomes:** Model temporal dependencies and process sequence data using RNN structures.

---

### 08. Emotion Recognition using ViT
**Concepts:** Vision Transformer for fine-grained classification, facial feature attention  
**Dataset:** Emotion datasets  
**Key Outcomes:** Leverage transformer-based attention mechanisms to recognise human emotions from facial images.

---

### 09. Denoising & Dimensionality Reduction using Autoencoders
**Concepts:** Encoder-decoder architecture, latent space, denoising autoencoder  
**Dataset:** Medical MNIST (or custom dataset)  
**Key Outcomes:** Use autoencoders for noise removal and compact feature representation.

---

### 10. Stable Diffusion with Hugging Face
**Concepts:** Diffusion models, text-to-image generation, Hugging Face `diffusers`  
**Dataset:** Text prompts  
**Key Outcomes:** Generate high-quality images from text prompts using Stable Diffusion pipelines.

---

## 🛠 Tools & Frameworks Used

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| TensorFlow / Keras | Model building & training |
| PyTorch | Alternative DL framework |
| Hugging Face `transformers` & `diffusers` | ViT, BERT, Stable Diffusion |
| OpenCV | Image preprocessing |
| Matplotlib / Seaborn | Visualisation |
| Google Colab | Cloud GPU execution |
| scikit-learn | Metrics & utilities |

---

## 📌 Submission Notes

- All notebooks are self-contained with outputs and markdown explanations.
- Each experiment follows the structure: **Objective → Theory → Code → Results → Conclusion**.
- Practical Exam held: **29th May 2026**

---

*Deep Learning Lab — M.Tech SEM II | © 2025–26*