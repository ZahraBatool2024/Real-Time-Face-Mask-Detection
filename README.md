<div align = "center">
  
# 😷 Real-Time-Face-Mask-Detection

Detects face masks in real-time using computer vision and deep learning.  

Efficient and accurate mask detection in webcam streams using CNN + OpenCV + Caffe SSD.


![Python](https://img.shields.io/badge/Python-3.8%2B-blue)![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)![OpenCV](https://img.shields.io/badge/OpenCV-Enabled-purple)![License](https://img.shields.io/badge/License-MIT-yellow)
---

## Table of Contents

</div>

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Trained Model](#trained-model)
- [Caffe SSD Face Detector](#caffe-ssd-face-detector)
- [Contact & Contribution](#contact--contribution)

---
<div align="center">
  
## Project Overview

</div>

This project implements a real-time face mask detection system using a custom CNN model.  
It detects multiple faces in live webcam feed and classifies each as **Mask 😷** or **No Mask ❌** with colored bounding boxes.

- Detects faces using **Caffe SSD** (`deploy.prototxt` + `.caffemodel`)
- Classifies face ROI as Mask / No Mask
- Displays live count of masked vs unmasked people

---
<div align ="center"> 
  
## Features
</div>

- ✅ Real-time detection using webcam  

- ✅ Face detection using Caffe SSD
  
- ✅ Mask / No Mask classification
  
- ✅ Colored bounding boxes and labels
  
- ✅ Live people counter
  
- ✅ Easy-to-use Python scripts
    
---
<div align = "center">
  
 ### Trained Model
</div>
Download the pretrained CNN model (mask_detector.pth) from Google Drive:

- Download mask_detector.pth [mask_cnn_model.pth](https://drive.google.com/file/d/1fr7n0EINDq0TaPWWSWtOrkDCk5oTvFVB/view?usp=sharing)  

- Place it in the model/ folder before running live_detection.py.

---

<div align="center">
  
### Technologies Used
<!-- First row: 3 badges, no space -->
<img src="https://img.shields.io/badge/PyTorch-CNN-red?logo=pytorch&logoColor=white"/><img src="https://img.shields.io/badge/OpenCV-Webcam-purple?logo=opencv&logoColor=white"/><img src="https://img.shields.io/badge/Face%20Mask-Classification-blue?logo=none"/><img src="https://img.shields.io/badge/Deep%20Learning-Enabled-orange?logo=none"/><img src="https://img.shields.io/badge/Caffe-SSD-yellow?logo=caffe&logoColor=white"/><img src="https://img.shields.io/badge/Python-PIL%2C%20NumPy-3.8%2B?logo=python&logoColor=white"/>

---

### Caffe SSD Face Detector

</div> 

Required files for accurate face detection:

- deploy.prototxt – Defines the SSD face detector architecture

- res10_300x300_ssd_iter_140000.caffemodel – Pretrained weights

---
<div align="center">
  
## Installation
</div>

```
Clone repository

git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection

Install dependencies

pip install -r requirements.txt 
```

<div align="center">
  
## Contact & Contribution

Have feedback, want to collaborate, or just say hello?  
Let’s connect and build something useful together.

📧 **Email:** zahraishaq2004@gmail.com    
💻 [GitHub Repo](https://github.com/ZahraBatool2024/Real-Time-Face-Mask-Detection)

Found this project useful? Give it a **star** on GitHub.  
Want to improve it? Submit a **Pull Request** and contribute to enhancing this system.

Your ideas and contributions help improve this real-time AI system.
</div>
