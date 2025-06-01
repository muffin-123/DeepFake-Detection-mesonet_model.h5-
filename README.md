
# 🧠 MesoNet Trained Model (Deepfake Detection)

This repository contains the **trained weights of a MesoNet-based deepfake detection model**, saved in `.h5` format. The model was trained on the [UADFV_dataset](https://www.kaggle.com/datasets/adityakeshri9234/uadfv-dataset) containing both real and fake face videos.

---

## 📁 Files in this Repository

| File                | Description                                        |
|---------------------|----------------------------------------------------|
| `mesonet_model.h5`  | Trained MesoNet model in Keras HDF5 format         |

---

## 🧠 Model Overview: MesoNet

- Lightweight CNN for detecting facial forgery in images
- Designed to detect subtle inconsistencies at the **mesoscopic level**
- Works on **256×256 facial frames**
- Outputs a probability score for classification: **Real or Fake**

> Based on the paper: [MesoNet: a Compact Facial Video Forgery Detection Network](https://arxiv.org/abs/1809.00888)

---

## 📊 Dataset Used

- **Dataset Name:** UADFV_dataset  
- **Source:** [Kaggle – UADFV_dataset](https://www.kaggle.com/datasets/adityakeshri9234/uadfv-dataset)
- Includes real and deepfake videos
- Frames extracted and resized to 256×256 for training

---

## 🚀 How to Use

1. **Clone this repo** or download the `.h5` file directly:

```bash
git clone https://github.com/muffin-123/mesonet-trained-model.git
cd mesonet-trained-model


