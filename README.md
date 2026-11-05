# 🛡️ Deepfake Detection – Robustness Analysis

<p align="center">
  <strong>An Interactive Research Paper Explorer</strong>
</p>

<p align="center">
  <a href="https://deepfake-research-ui.vercel.app/">
    🌐 **Live Website**
  </a>
</p>

---

## 📌 About the Project

Deepfake technology has made it increasingly difficult to distinguish between real and manipulated media. Although deepfake detection models often achieve good performance on clean images, their reliability can decrease under adversarial attacks and real-world distortions.

This project presents an interactive exploration of our research paper:

**"Robustness Analysis of Spatial, Frequency, and Spatial-Frequency Fusion-Based DeepFake Detectors under Adversarial and Real-World Distortions."**

The project focuses on understanding and comparing the robustness of three different deepfake detection approaches under challenging conditions.

## 🎯 Research Objectives

- Analyze the robustness of spatial-based deepfake detectors.
- Evaluate frequency-based detection using DCT features.
- Study spatial-frequency fusion-based detection.
- Examine model performance under adversarial attacks.
- Evaluate the impact of real-world image distortions.
- Compare the strengths and limitations of all three approaches.

## 📂 Dataset

**Celeb-DF v2**

- Contains real and fake celebrity videos.
- Five frames are extracted from each video.
- Used to evaluate the three detector architectures under consistent experimental settings.

## 🧠 Detection Approaches

### 1. Spatial-Based Detection
Uses visual and spatial features extracted from images to identify manipulated facial content.

### 2. Frequency-Based Detection
Uses Discrete Cosine Transform (DCT) features to identify frequency-domain patterns associated with manipulated content.

### 3. Spatial-Frequency Fusion
Combines spatial and frequency information to evaluate whether feature fusion improves deepfake detection robustness.

## ⚙️ Methodology

The research follows a systematic evaluation process:

1. Dataset preparation and frame extraction.
2. Development of three detector architectures.
3. Model training and evaluation on clean images.
4. Testing under adversarial attacks.
5. Testing under real-world distortions.
6. Comparative robustness analysis.

## ⚔️ Adversarial Attacks

The following attacks are evaluated:

- **FGSM:** Fast Gradient Sign Method.
- **PGD:** Projected Gradient Descent.

These attacks are used to study how small adversarial changes affect the predictions of deepfake detectors.

## 🌍 Real-World Distortions

The models are also evaluated under:

- JPEG Compression
- Gaussian Noise
- Gaussian Blur
- Image Resizing
- Compound Distortions

Compound testing evaluates the effect of multiple distortions applied sequentially.

## 📊 Evaluation Metrics

The research uses the following performance metrics:

| Metric | Purpose |
|---|---|
| Precision | Measures the correctness of fake predictions |
| Recall | Measures how many actual fake samples are detected |
| F1-Score | Balances precision and recall |
| ROC-AUC | Measures class separation capability |
| Balanced Accuracy | Considers both classes equally |

## 🔍 Key Findings

- Spatial and fusion models perform strongly on clean images and under noise.
- FGSM and PGD attacks reduce the performance of all three detectors.
- JPEG compression significantly affects recall.
- Frequency-based detection performs comparatively weaker in most tested conditions.
- Fusion does not consistently outperform spatial-based detection.
- High performance on clean images does not necessarily guarantee robustness in real-world conditions.

**Key Observation:** No single detector performs best under every testing condition. Combining spatial and frequency features does not automatically guarantee better robustness.

## 🚀 Future Scope

- Evaluate models on additional deepfake datasets.
- Experiment with different distortion strengths.
- Perform experiments using multiple random seeds.
- Explore improved fusion strategies.
- Investigate more robust deepfake detection architectures.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript

## 🌐 Live Website

Explore the interactive research paper:

**https://deepfake-research-ui.vercel.app/**

## 👨‍💻 Research Team

| Team Member | Contribution |
|---|---|
| Rashika Choudhary | Research & Development |
| Satyam Tyagi | Research & Development |
| Pranjal Sharma | Research & Development |
| Mayan Prajapati | Research & Development |
| Rachit Gupta | Research & Development |

## 📚 References

The research is based on existing literature on deepfake detection, adversarial robustness, and image processing.

Key references include:

1. Deepfake Detection: A Systematic Literature Review (IEEE Access, 2022).
2. Towards Universal Fake Image Detectors That Generalize Across Generative Models (CVPR, 2023).
3. Adversarial Threats to DeepFake Detection: A Practical Perspective (CVPR Workshops, 2021).
4. Celeb-DF: A Large-Scale Challenging Dataset for DeepFake Forensics (CVPR, 2020).
5. Explaining and Harnessing Adversarial Examples (ICLR, 2015).

---

<p align="center">
  **Built with research, technology, and a focus on digital authenticity.**
</p>
