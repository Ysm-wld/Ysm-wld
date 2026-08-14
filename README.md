<!--
  =========================================================================
  README.md — GitHub profile for Yasmin Walid Abou Elsaad
  =========================================================================
-->

<!-- ============================ HERO ============================ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,100:161b22&height=150&section=header&text=Yasmin%20Walid%20Abou%20Elsaad&fontSize=28&fontColor=00d4ff&fontAlignY=45&desc=AI%20%2F%20Robotics%20Engineer&descAlignY=68&descColor=8b949e&descSize=15" />
</p>

<h3 align="center">I build systems that perceive, understand, decide, and act.</h3>

<p align="center">
  <a href="mailto:yasmin.wld4@gmail.com"><img src="https://img.shields.io/badge/-yasmin.wld4@gmail.com-0d1117?style=flat-square&logo=gmail&logoColor=00d4ff" /></a>
  <a href="https://www.linkedin.com/in/yasmin-walid"><img src="https://img.shields.io/badge/-LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=00d4ff" /></a>
  <a href="[ADD PAPER DOI LINK]"><img src="https://img.shields.io/badge/-Published_Research-0d1117?style=flat-square&logo=arxiv&logoColor=7c3aed" /></a>
</p>

<br/>

I'm an AI & Robotics Engineering student at the Arab Academy for Science & Technology (Intelligent Systems & Robotics, GPA 3.9), based in Alexandria, Egypt. Most of what I build ends up touching a camera, a sensor, or a motor at some point — I like AI that has to survive contact with the real world, not just a validation set. My work spans computer vision, autonomous navigation, multimodal AI, and edge deployment, and one system I led to navigation went on to win Egypt's national RoboCup@Home championship.

<br/>

<!-- ============================ SIGNATURE VISUAL ============================ -->
<p align="center">
  <img src="assets/hero/signature.svg" width="100%" alt="Perceive, Understand, Decide, Act, Deploy pipeline" />
</p>
<p align="center"><sub>The shape most of what's below actually takes — sensing in, a decision made, something physical happens.</sub></p>

<br/>

## What I've built

> Screenshots/GIFs referenced below live in `/assets/projects/` — see the asset list at the end. Nothing here is a mockup; placeholders are marked explicitly.

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
<tr><td>

**Benchmarking YOLOv8–YOLOv12 for Real-Time Object Detection on SBCs**
`Preprints.org` · Published 2026 · DOI: [10.20944/preprints202605.0936.v1](https://doi.org/10.20944/preprints202605.0936.v1)

Benchmarked five YOLO generations (v8–v12) on resource-constrained single-board computers, evaluating inference latency, accuracy tradeoffs, and real-world deployment feasibility for edge AI and embedded robotics.

`[ADD BENCHMARK CHART: latency vs. accuracy across models/hardware]`

</td></tr>
<tr><td>

**Multimodal Wearable Dataset for Arabic Sign Language Recognition** — *in progress*

Building a public dataset from flex + IMU sensor fusion for Arabic Sign Language alphabet recognition — the research extension of IntelliGlove, aimed at advancing inclusive, multimodal human-computer interaction.

</td></tr>
</table>

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
  <img src="https://github-readme-stats.vercel.app/api?username=[ADD_GH_USERNAME]&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="150"/>
</p>
</details>

<br/>

<p align="center">
  <sub>Alexandria, Egypt</sub>
</p>
