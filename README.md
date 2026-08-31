<div align="center">

![Noru-Kang Banner](https://capsule-render.vercel.app/api?type=waving&color=363636&height=150&section=header&text=Noru-Kang&fontSize=50&fontColor=FFD700&fontAlign=20&fontAlignY=30)

<img src="https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2FNoru-Kang&label=Noru-Kang&icon=github&color=%23fd7e14&message=&style=flat&tz=ROK">

### TaeYoung Kang

**Applied Statistics Major · Software Double Major · Chung-Ang University**

I am interested in **Foundation Model Adaptation** and **Representation Learning under Distribution Shift**.

My research experience spans **ECG, EEG, PSG, audio, and speech**, with a particular focus on how pretrained representations behave when the **source, site, subject, session, device, or data condition changes**.

I am particularly interested in:

**Foundation Models & Representation Learning**  
**Domain Generalization & Robustness**  
**Source-Free / Test-Time Adaptation**  
**Parameter-Efficient & Representation-Level Adaptation**  
**Cross-Domain & Multimodal Learning**

I worked as a **Research Student at the CAU-ET AI Lab** from **Jul. 2024 to Aug. 2026**, conducting deep-learning research on physiological signals, foundation-model representations, and domain generalization.

[![Blog](https://img.shields.io/badge/Research%20Blog-Noru--Kang.github.io-181717?style=flat-square&logo=github)](https://noru-kang.github.io/)
[![Email](https://img.shields.io/badge/Email-taey.kg%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:taey.kg@gmail.com)

</div>

---

## 🔬 Research Interests

- **Foundation Models & Representation Learning**
  - Pretrained representations for biosignals and general time-series
  - Foundation-model transfer to downstream tasks

- **Domain Generalization & Adaptation**
  - Site, subject, session, device, and acquisition-condition shift
  - Source-free and test-time adaptation
  - Robustness under unseen domains

- **Efficient Adaptation**
  - Selective Unfreezing
  - LoRA / Parameter-Efficient Fine-Tuning
  - Representation-Level Intervention

- **Cross-Domain & Multimodal Learning**
  - Biosignal ↔ Audio / Speech
  - Extension toward Vision and Multimodal Foundation Models

---

## 🧪 Selected Research

### PhysioNet Challenge 2026 — PSG Foundation Model & Representation Steering
**Mar. 2026 – Present**

- Built a downstream prediction pipeline for future cognitive impairment using representations from a pretrained **PSG Foundation Model**
- Kept the Foundation Model frozen and constructed record-level representations from multimodal PSG
- Applied **Sparse Autoencoder (SAE)-based Representation Steering** to identify and manipulate site-associated latent features
- Investigated whether representation-level intervention can improve robustness under **recording-site domain shift**
- Conducted Foundation Model and modality ablation experiments
- Built the end-to-end training and inference pipeline for challenge submission

**Research question:**  
Can domain-specific information in a pretrained representation be selectively modified while preserving task-relevant information?

---

### EEG-AAD — Foundation Model Adaptation
**Oct. 2025 – Nov. 2025**

- Applied a pretrained **EEG Foundation Model** as the backbone for Auditory Attention Decoding
- Designed and implemented a **128 → 200 Hz TemporalResampler** to handle sampling-rate mismatch
- Implemented a two-stage **Cold Start → Selective Unfreezing** training strategy
- Compared encoder unfreezing ratios of **10%, 30%, and 50%**
- Investigated performance changes under **audio-only → audio-visual condition shift**

**Research question:**  
Which parts of a pretrained Foundation Model should be adapted when the downstream data distribution changes?

---

### PhysioNet Challenge 2025 — Chagas Disease Detection from ECG
**Mar. 2025 – Dec. 2025**

- Developed a hybrid model combining **1D ResNet-BiGRU representations** with physiologically motivated handcrafted ECG features
- Designed and implemented **RBBB/LAFB-related features** based on clinical literature
- Improved large-scale ECG preprocessing efficiency by analyzing and restructuring computational bottlenecks
- Conducted experiments on **cross-source robustness and domain shift**
- Extended challenge work into a journal paper published in **Physiological Measurement**
- **Co-first author**

**Research insight:**  
Strong internal validation performance did not consistently transfer to independent cohorts, motivating my continued interest in **Domain Shift and Generalization**.

---

### TidyVoice 2026 — Speaker Verification
**Jan. 2026 – Feb. 2026**

- Built fine-tuning and inference pipelines using a pretrained speaker-verification backbone
- Optimized PyTorch DataLoader configuration and parallelized sample-wise **fbank extraction**
- Implemented **Checkpoint / Resume** and **S-Norm / Cohort Embedding**
- Reduced training epoch time from approximately **25 minutes to 15 minutes**

**Research focus:**  
Efficient and reproducible experimentation with pretrained audio models.

---

## 📄 Publications

**T. Kang\*** et al.  
**“Auxiliary-conditioned Cross-Attention with Physiologically Interpretable Features for Chagas Disease Detection from 12-lead ECGs.”**  
*Physiological Measurement*, 2026.  
\* Equal contribution (Co-first author)

**T. Kang** et al.  
**“ResNet-BiGRU with Conditioned Query-Based Cross-Attention and Weighted Loss for Automated Chagas Disease Detection from 12-Lead ECG.”**  
*Computing in Cardiology (CinC 2025)*, São Paulo, Brazil, 2025.

---

## 📚 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- Paper Follow Up - 26.08 5주차 [**[바로가기]**](https://noru-kang.github.io/posts/Paper-Follow-Up-26.08-5%EC%A3%BC%EC%B0%A8/)
- Paper Follow Up - 26.08.4주차 [**[바로가기]**](https://noru-kang.github.io/posts/26.08.4%EC%A3%BC%EC%B0%A8/)
- SAE(Sparse AutoEncoder), Steering Vector [**[바로가기]**](https://noru-kang.github.io/posts/SAE(Sparse-AutoEncoder),-Steering-Vector/)
- tidyvocie2026 [**[바로가기]**](https://noru-kang.github.io/posts/tidyvoice2026/)
- 한국어 학습자를 위한 노래 추천 시스템 [**[바로가기]**](https://noru-kang.github.io/posts/korean/)

<!-- BLOG-POST-LIST:END -->

---

## 🛠️ Research Stack

### Machine Learning / Deep Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

### Signal / Biosignal / Audio

![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![MNE](https://img.shields.io/badge/MNE-EEG%20%2F%20MEG-4C72B0?style=flat-square)
![librosa](https://img.shields.io/badge/librosa-Audio-orange?style=flat-square)
![torchaudio](https://img.shields.io/badge/torchaudio-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

### Research Engineering

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

- Large-scale dataset preprocessing and management
- Linux / SSH-based GPU server experiments
- Reproducible training and inference pipelines
- Experiment logging, checkpointing, and ablation studies

---

<div align="center">

### Links

[![GitHub](https://img.shields.io/badge/GitHub-Noru--Kang-181717?style=flat-square&logo=github)](https://github.com/Noru-Kang)
[![Blog](https://img.shields.io/badge/Blog-Noru--Kang.github.io-181717?style=flat-square&logo=githubpages)](https://noru-kang.github.io/)
[![Gmail](https://img.shields.io/badge/Gmail-taey.kg%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:taey.kg@gmail.com)

</div>
