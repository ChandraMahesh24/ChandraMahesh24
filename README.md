<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1822,100:22d3ee&height=200&section=header&text=Mahesh%20Chandra&fontSize=52&fontColor=dff4ff&animation=fadeIn&fontAlignY=38&desc=AI%20%26%20Computer%20Vision%20Engineer&descAlignY=60&descSize=20" width="100%" alt="Mahesh Chandra banner"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=700&lines=YOLOv8+%2F+YOLO11+Object+Detection;ANPR+%26+OCR+Pipelines;Real-Time+Video+Analytics;Edge+AI+on+NVIDIA+Jetson;From+pixels+to+production" alt="Typing animation"/>
</p>

<p align="center">
  <a href="https://chandramahesh24.github.io">
    <img src="https://img.shields.io/badge/%E2%96%B6%20Live%20Interactive%20Portfolio-Open-22d3ee?style=for-the-badge&labelColor=0b1822" alt="Live portfolio"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/ChandraMahesh24"><img src="https://img.shields.io/badge/GitHub-ChandraMahesh24-181717?style=for-the-badge&logo=github" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/mahesh-chandra-63440a239"><img src="https://img.shields.io/badge/LinkedIn-Mahesh%20Chandra-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mahesh.mahi.cnd@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=chandramahesh24&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile views"/>
</p>

---

## `> about`

I'm an **AI Engineer** specializing in **Computer Vision, Deep Learning, OCR, ANPR and Edge AI**, with hands-on experience building AI solutions for real industrial applications.

My work covers the full lifecycle:

```text
Data preparation → Annotation → Preprocessing → Training → Evaluation → Optimization → Deployment
```

I enjoy solving hard computer vision problems, improving model accuracy, optimizing inference speed, and turning models into reliable real-world applications.

> 🟢 **Open to opportunities** in AI Engineering, Computer Vision, Deep Learning, Machine Learning and Edge AI.

---

## `> tech stack`

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLOv8"/>
  <img src="https://img.shields.io/badge/YOLO11-00BFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLO11"/>
  <img src="https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge&logo=roboflow&logoColor=white" alt="Roboflow"/>
  <img src="https://img.shields.io/badge/PaddleOCR-2932E1?style=for-the-badge&logo=paddlepaddle&logoColor=white" alt="PaddleOCR"/>
  <img src="https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX Runtime"/>
  <img src="https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Jetson"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

<details>
<summary><b>More about my expertise (click to expand)</b></summary>

<br>

| Area | What I do |
|---|---|
| **Detection** | YOLOv8 / YOLO11, object detection, object tracking, real-time video analytics |
| **OCR / ANPR** | PaddleOCR, OCR post-processing, license plate recognition, multi-frame voting |
| **Data** | Roboflow, dataset engineering, annotation review, class balancing, hard-negative analysis |
| **Optimization** | ONNX Runtime, model optimization, memory and latency tuning |
| **Edge** | NVIDIA Jetson, RTSP / CCTV streams |
| **Monitoring** | ROI and zone-based monitoring, alert systems |
| **Pipelines** | Configurable AI pipelines using JSON / YAML, SQLite event storage |

</details>

---

## `> projects`

<details open>
<summary><b>🚘 ANPR / License Plate Recognition</b></summary>

<br>

Vehicle → plate → OCR, built for blurry, angled, real CCTV frames.

```mermaid
flowchart LR
  A[CCTV Frame] --> B[Vehicle Detection]
  B --> C[Plate Detection]
  C --> D[ROI Extraction]
  D --> E[Deskew + Refine]
  E --> F[Enhance]
  F --> G[OCR]
  G --> H[Multi-frame Voting]
  H --> I[Regex Validation]
  I --> J((Final Plate))
```

`YOLO11` `OpenCV` `PaddleOCR` `ONNX Runtime` `Python`

</details>

<details>
<summary><b>📦 Industrial Object Detection</b></summary>

<br>

- Sack bag, tin and carton box detection
- Plywood detection
- Dataset engineering and accuracy tuning for real plant lighting

`YOLOv8` `Roboflow` `PyTorch` `OpenCV`

</details>

<details>
<summary><b>👥 Person Detection & Counting</b></summary>

<br>

- Person detection with object tracking across frames
- Counting with zone lines
- Real-time video analytics

`YOLO11` `Tracking` `OpenCV` `Python`

</details>

<details>
<summary><b>🦺 PPE Detection & Compliance Monitoring</b></summary>

<br>

- Helmet and safety equipment detection
- Dataset balancing, annotation review, hard-negative analysis
- Compliance monitoring and alerts

`YOLOv8` `Roboflow` `PyTorch` `OpenCV`

</details>

<details>
<summary><b>🔥 Fire & Smoke Detection</b></summary>

<br>

- Real-time detection with instant alerts
- False-positive analysis and retraining
- Deployment testing on live streams

`YOLOv8` `RTSP` `Jetson` `SQLite`

</details>

<details>
<summary><b>🚗 Vehicle Detection & Classification</b></summary>

<br>

- Multiple vehicle classes on CCTV streams
- Camera angle and positioning analysis
- Model performance evaluation

`YOLO11` `OpenCV` `ONNX Runtime` `NumPy`

</details>

<details>
<summary><b>📍 ROI / Zone-based Monitoring & Alerts</b></summary>

<br>

- Per-camera ROI and zone rules
- Configurable pipelines in JSON / YAML
- Events and alerts stored in SQLite

`OpenCV` `JSON/YAML` `SQLite` `Python`

</details>

---

## `> how I build models`

```mermaid
flowchart TD
  A[Dataset collection + cleaning] --> B[Annotation + validation]
  B --> C[YOLO training]
  C --> D{Evaluate: P / R / F1 / mAP}
  D -->|errors found| E[Error analysis: false positives, hard negatives]
  E --> C
  D -->|good enough| F[Optimize: ONNX, memory, latency]
  F --> G[Real-time testing on live streams]
  G --> H[Edge deployment]
```

I care about what happens after training: camera position, image quality, preprocessing, dataset quality and inference speed often matter as much as the model itself.

---

## `> github stats`

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chandramahesh24&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=github" width="48%" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chandramahesh24&layout=compact&hide_border=true&theme=tokyonight" width="48%" alt="Top languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chandramahesh24&hide_border=true&theme=tokyonight" width="60%" alt="GitHub streak"/>
</p>

---

## `> connect`

<p align="center">
  <a href="https://chandramahesh24.github.io"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/mahesh-chandra-63440a239"><b>LinkedIn</b></a> ·
  <a href="mailto:mahesh.mahi.cnd@gmail.com"><b>Email</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,100:0b1822&height=120&section=footer" width="100%" alt="footer"/>
</p>
