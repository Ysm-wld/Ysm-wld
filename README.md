<!--
  =========================================================================
  README.md — GitHub profile for Yasmin Walid Abou Elsaad
  =========================================================================
-->

<h1 align="center">

$\Huge{\color{#14B8A6}\textsf{Yasmin Walid}}$

</h1>

<h3 align="center">AI / Robotics Engineer</h3>
<p align="center">Computer Vision · Autonomous Systems · Edge AI · Multimodal Intelligence</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Segoe+UI&size=15&pause=1400&color=5EEAD4&center=true&vCenter=true&width=600&lines=National+robotics+champion+%E2%80%94+RoboCup%40Home+Egypt+2025;Co-author%2C+peer-reviewed+edge-AI+research" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:yasmin.wld4@gmail.com"><img src="https://img.shields.io/badge/-Email-151A1A?style=flat-square&logo=gmail&logoColor=5EEAD4" /></a>
  <a href="https://www.linkedin.com/in/yasmin-walid"><img src="https://img.shields.io/badge/-LinkedIn-151A1A?style=flat-square&logo=linkedin&logoColor=5EEAD4" /></a>
  <a href="https://www.mdpi.com/2504-4990/8/7/204"><img src="https://img.shields.io/badge/-Published_Research-151A1A?style=flat-square&logo=readdotcv&logoColor=14B8A6" /></a>
</p>

<br/>

I'm an AI & Robotics Engineering student at the Arab Academy for Science & Technology (Intelligent Systems & Robotics, GPA 3.9), based in Alexandria, Egypt. Most of what I build ends up touching a camera, a sensor, or a motor at some point — I'm drawn to AI that has to survive contact with the real world, not just a validation set. My work spans computer vision, autonomous navigation, multimodal AI, and edge deployment, and one navigation system I led went on to win Egypt's national RoboCup@Home championship.

<br/>

<p align="center">
  <img src="assets/hero/signature.svg" width="100%" alt="Perceive, Understand, Decide, Act, Deploy pipeline" />
</p>
<p align="center"><sub>The shape most of what's below actually takes — sensing in, a decision made, something physical happens.</sub></p>

<br/>

## What I've built

> Screenshots/GIFs referenced below belong in `assets/projects/` — see the asset list at the end. Nothing here is a mockup; placeholders are marked explicitly.

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Autonomous Home Robot
**Problem:** A service robot has to navigate, localize, and act in a home environment it's never seen, in real time.

**System:** Full navigation stack — SLAM for mapping and localization, ML-based path planning, inverse kinematics for manipulation, and a real-time object detection pipeline feeding it all.

**My role:** Built the navigation system end-to-end and led integration across the perception and motion-control subsystems.

**Result:** 🥇 1st Place, RoboCup@Home Egypt National Championship (2025) — up from 4th place the year before.

`ROS` `SLAM` `Inverse Kinematics` `Path Planning` `Real-time Object Detection`

`[ADD REPO LINK]` · `[ADD DEMO GIF]`

</td>
<td width="50%" valign="top">

### 🧤 IntelliGlove
**Problem:** Arabic Sign Language has limited real-time translation tools, and most existing hardware is expensive or bulky.

**System:** A wearable glove that fuses flex-sensor and IMU data through an ML classifier to translate gestures into text and speech in real time.

**Challenge:** Making gesture classification reliable on noisy sensor data with lightweight, affordable hardware.

**Status:** Working prototype; the underlying dataset is being extended into a public research dataset (see Research, below).

`Flex Sensors` `IMU` `Sensor Fusion` `Embedded ML`

`[ADD REPO LINK]` · `[ADD DEMO GIF]`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎧 Multimodal Perception — Vision + Audio + Text
**Problem:** Most captioning/description systems reason over a single modality. I wanted to know whether they should have to.

**System:** An architecture fusing a Vision Transformer (image), Whisper/Wav2Vec (audio), and BERT/T5 (text) over the Flickr8k dataset, comparing fusion strategies — feature concatenation, cross-attention, and late fusion.

**Challenge:** Investigating whether SimCLR self-supervised pretraining on the visual encoder improves downstream multimodal performance versus a non-pretrained baseline.

**Status:** Exploratory/research build — architecture and comparison implemented; results not yet published.

`Vision Transformer` `Whisper/Wav2Vec` `BERT/T5` `Cross-Attention` `SimCLR`

`[ADD REPO LINK]` · `[ADD RESULTS WHEN AVAILABLE]`

</td>
<td width="50%" valign="top">

### 📱 Eduro
**Problem:** Students juggling study workflows rarely have tools that adapt to how they actually work.

**System:** A full-stack Flutter mobile app combining study automation with personalized AI guidance.

`Flutter` `Dart`

`[ADD REPO LINK]`

</td>
</tr>
</table>

<br/>

<!-- ============================ RESEARCH ============================ -->
## Research

<table>
<tr>
<td width="14" style="background-color:#14B8A6;"></td>
<td>

<sub><b>PUBLISHED · PEER-REVIEWED JOURNAL ARTICLE</b></sub>

### Benchmarking YOLOv8–YOLOv12 for Real-Time Object Detection on Single-Board Computers

**Journal:** *Machine Learning and Knowledge Extraction* (MDPI) · Vol. 8, Issue 7, Article 204
**Published:** 13 July 2026 · **DOI:** [10.3390/make8070204](https://doi.org/10.3390/make8070204)

A comprehensive benchmark of YOLOv8 through YOLOv12 across single-board computers — Raspberry Pi 4/5, NVIDIA Jetson Nano, Jetson Orin, and LattePanda — under different power modes, evaluating inference speed (FPS), detection accuracy (mAP), RAM usage, and computational complexity (FLOPs) for real-time edge deployment.

Co-authored with a research team spanning Ajman University, Heriot-Watt University Dubai, and the Arab Academy for Science, Technology & Maritime Transport. My contribution included hands-on benchmark execution across the SBC platforms, alongside literature review, data interpretation, and results visualization.

```text
YOLOv8 → YOLOv9 → YOLOv10 → YOLOv11 → YOLOv12
                     │
              Edge Deployment
     (Raspberry Pi · Jetson · LattePanda)
                     │
       FPS  ·  mAP  ·  RAM  ·  FLOPs
```

<a href="https://www.mdpi.com/2504-4990/8/7/204"><img src="https://img.shields.io/badge/Read_the_Article-14B8A6?style=for-the-badge&logoColor=white" /></a>

</td>
</tr>
</table>

<br/>

**Multimodal Wearable Dataset for Arabic Sign Language Recognition** — *in progress*
Building a public dataset from flex + IMU sensor fusion for Arabic Sign Language alphabet recognition — the research extension of IntelliGlove.

<br/>

<!-- ============================ ECOSYSTEM ============================ -->
## Ecosystem

**Perceive** — `OpenCV` `YOLOv8–v12` `HOG/SIFT` `CNNs (VGG16, ResNet)`
**Understand** — `PyTorch` `TensorFlow` `Vision Transformers` `Transformers (BERT/T5)` `Scikit-learn`
**Decide / Act** — `ROS` `SLAM` `Path Planning` `Inverse Kinematics`
**Deploy** — `Arduino` `ESP32` `Embedded C` `Edge inference on SBCs`
**Build** — `Python` `C/C++` `SQL` `Flutter/Dart` `Linux · Red Hat` `Docker` `Git`

<br/>

<!-- ============================ ADDITIONAL SYSTEMS EXPERIENCE ============================ -->
<details>
<summary><b>Additional systems experience</b> — security engineering</summary>
<br/>

Architected and deployed a full SIEM/SOC pipeline (Sep 2025 – Jan 2026), integrating Wazuh (log correlation & threat detection), OpenSearch (behavior analytics), Suricata (network detection), and OpenEDR (endpoint detection), with MISP for threat intelligence and Shuffle for automated incident-response playbooks.

`Wazuh` `OpenSearch` `Suricata` `OpenEDR` `MISP` `Shuffle`

</details>

<br/>

## Currently exploring

- Explainable decision-making in perception systems with real uncertainty, not just confidence scores
- Whether self-supervised pretraining actually earns its cost on small multimodal datasets
- Getting more of the above running natively on-device rather than off-loading to a server

<br/>

<!-- ============================ STATS ============================ -->
<details>
<summary>GitHub stats</summary>
<br/>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=[ADD_GH_USERNAME]&show_icons=true&theme=github_dark&hide_border=true&count_private=true&icon_color=14B8A6&title_color=5EEAD4&text_color=9CA3AF&bg_color=0B0F0F" height="150"/>
</p>
</details>

<br/>

<p align="center">
  <sub style="color:#9CA3AF">Alexandria, Egypt</sub>
</p>
