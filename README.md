<div align="center">

<a href="https://aisoltani.github.io">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=820&lines=Computer+Vision+%26+Machine+Learning+Engineer;Medical+AI+%E2%80%A2+Remote+Sensing+%E2%80%A2+Real-Time+Edge+AI;Vision-Language+Models+%E2%80%A2+LLMs+%E2%80%A2+RAG;Vision+systems+that+work+outside+the+lab" alt="Amir Soltani: computer vision and machine learning engineer" />
</a>

<br/>

**Senior computer vision and machine learning engineer.** Since 2016 I've built vision systems that have to work outside the lab:<br/>
on a phone in a gym, on a drone above a fire line, on a Jetson in a truck cab, on a clinician's review screen.

<a href="https://aisoltani.github.io"><img src="https://img.shields.io/badge/Portfolio-aisoltani.github.io-2F81F7?style=for-the-badge" alt="Portfolio" /></a>
<a href="mailto:amirsoltani.os@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/amir-soltani-aisoltani/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://www.kaggle.com/aisoltani"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>
<a href="https://x.com/AISoltani"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>

</div>

---

## About

<img align="right" width="330" src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/as2.gif" alt="" />

- 🧠 **10+ years** across the whole model lifecycle: data and annotation, training, evaluation, inference optimization, deployment
- 🏥 **Medical AI:** weakly supervised 3D detection for MRI and CT, dental X-rays, brain-tumour segmentation (0.92 DSC on BraTS), skin-lesion triage on Jetson Nano
- 🛰️ **Remote sensing:** Prithvi-100M on Sentinel-2, small objects in large satellite scenes with SAHI, thermal drones for early fire detection (23% fewer false alarms)
- ⚡ **Real-time and edge:** under 15 ms on Jetson Orin Nano and under 30 ms on mobile, with ONNX Runtime, TensorRT and DeepStream
- 🏋️ **Led ML and computer vision at Sculp AI:** form feedback for 40+ exercises, body-composition segmentation (Dice 0.94)
- 🤖 **Now:** vision-language models (CLIP, DINOv2, SigLIP, Grounding DINO, SAM 3), retrieval and LLM pipelines for clinical data
- 🎯 *"Knowledge is not skill. Knowledge plus ten thousand hours is skill."*

<br clear="right"/>

---

## Experience

| Period | Role | Where | Focus |
|---|---|---|---|
| May 2025 – Oct 2026 | Computer Vision Researcher | Nova Vision (remote, part-time) | Multimodal clinical AI, VLM retrieval, LLM document pipelines |
| Jan 2023 – Feb 2025 | Computer Vision Engineer | VRVis GmbH (remote, flexible schedule) | Satellite, UAV and thermal drone imagery |
| Feb 2022 – Mar 2024 | Head of ML & Computer Vision | Sculp AI (remote, full-time) | Real-time pose, body-composition segmentation, mobile deployment |
| Feb 2022 – Dec 2023 | Computer Vision Engineer | SoftwareMotion (remote, project-based) | ADAS tracking and driver monitoring on Jetson |
| Sep 2020 – Dec 2021 | Computer Vision Researcher | G42 Healthcare (remote, part-time) | MRI, CT, dental X-ray and skin-lesion analysis |
| Feb 2016 – Mar 2019 | AI Computer Vision Developer | AMA-CTRL (Shiraz, on-site) | Industrial monitoring and site-safety vision |

🎓 M.Sc. Computer Engineering (Artificial Intelligence), Amirkabir University of Technology (Tehran Polytechnic). Thesis: *Few-shot Cascade R-CNN for Human Forensic Age Estimation*.

---

## Foundation models, VLMs and LLMs

> Connecting perception models to language and retrieval.

| | What | Built with | Where |
|---|---|---|---|
| 🩺 | **Finding visually similar clinical cases:** embedding search so reviewers can pull up similar cases during triage | `CLIP` `DINOv2` `SigLIP` | Nova Vision |
| 🗣️ | **Masks from a text prompt:** text-guided localization and mask generation for image review and annotation | `Grounding DINO` `SAM 3` | Nova Vision |
| 📄 | **Clinical documents into structured records:** extraction of diagnoses, medications and lab results, plus retrieval-backed assistants for search, summaries and Q&A | `OCR` `LLMs` `RAG` | Nova Vision |
| 📚 | **Clinical knowledge assistant:** chunking, retrieval, reranking and answers grounded in the source material | `LLM` `RAG` | Independent prototype |
| 🔎 | **Search medical cases by text or image:** shared visual and text embeddings with a language-model layer that summarizes the evidence | `VLM` | Independent prototype |
| 🌍 | **Geospatial foundation models:** fine-tuned for forest-cover classification and other Earth-observation tasks | `Prithvi-100M` `Clay` | VRVis and research |

---

## Featured work

**62 searchable projects are on [aisoltani.github.io](https://aisoltani.github.io).** A few with pictures:

### Detecting medical targets from a handful of examples

Few-shot Cascade R-CNN for detection and segmentation in medical images. [Code](https://github.com/AISoltani/Mask_RCNN_ResNet_101_50)

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/Mask_RCNN_ResNet_101_50/refs/heads/main/Few-shot.gif" width="78%" alt="Few-shot medical detection">
</p>

### Super-resolution that helps find small medical targets

Super-resolution as a front end for 2D and 3D detection.

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/labelbox/refs/heads/master/MedicalSR.png" width="78%" height="400" alt="Super-resolution-driven medical detection">
</p>

### Tracking muscle and fat change between training sessions

Muscle and fat segmentation with repeat-session alignment: Dice 0.94 and mAP@50 0.92 on the internal benchmark, with a distilled model under 35 MB for mid-range phones.

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/1.gif" width="27%" alt="Muscle segmentation demo 1" />
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/2.gif" width="27%" alt="Muscle segmentation demo 2" />
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/33.gif" width="27%" alt="Muscle segmentation demo 3" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/labelbox/refs/heads/master/Muscle.png" width="88%" alt="Muscle segmentation overview" />
</p>

### Body pose, keypoints and shape from several models

Multiple body pose, point and shape estimation with MoveNet, PoseNet and MediaPipe.

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/pose.png" width="90%" alt="Pose estimation comparison">
</p>

### Thermal detection that ignores the colormap

A real-time hybrid YOLO-Transformer detector that stays reliable across thermal colormap settings.

<p align="center">
  <img src="https://github.com/AISoltani/labelbox/blob/master/Thermal-DT.gif?raw=true" width="78%" alt="Thermal object detection">
</p>

### Small objects in whole Sentinel satellite scenes

Sliced inference with horizontal and oriented boxes, so large scenes can be processed without losing small targets.

<p align="center">
  <img src="https://github.com/AISoltani/labelbox/blob/master/Sentinel.gif?raw=true" width="48%" alt="Detection on Sentinel imagery">
</p>

### YOLOv11-EdgeSuite: detection and segmentation on Android

A mobile vision toolkit that runs YOLOv11 models on smartphones. [Code](https://github.com/AISoltani/Yolov11-Android-Tool-Kotlin)

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/Yolov11-Android-Tool-Kotlin/refs/heads/main/SCR1.jpg" width="27%" alt="YOLOv11 Android screenshot 1">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://raw.githubusercontent.com/AISoltani/Yolov11-Android-Tool-Kotlin/refs/heads/main/SCR2.jpg" width="27%" alt="YOLOv11 Android screenshot 2">
  &nbsp; &nbsp; &nbsp; &nbsp;
  <img src="https://raw.githubusercontent.com/AISoltani/Yolov11-Android-Tool-Kotlin/refs/heads/main/SRC3.jpg" width="27%" alt="YOLOv11 Android screenshot 3">
</p>

### Fashion recommendations from a few examples

Few-shot recommendation that combines metric learning with lightweight content-based filtering.

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/AISoltani/main/.github/workflows/ScreenShot_20231103191154.png" width="88%" alt="Few-shot fashion recommendation">
</p>

### Density heatmaps from a few labelled examples

<p align="center">
  <img src="https://raw.githubusercontent.com/AISoltani/labelbox/refs/heads/master/HeatMap.png" width="78%" height="400" alt="Few-shot object density heatmap" />
</p>

---

## Industrial vision systems

> Vision for smart infrastructure, site safety and traffic analytics.

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/AISoltani/Vison_advanced/refs/heads/main/Parking-AS.png" width="100%" alt="Smart parking"/><br/>
      <b>Smart parking occupancy and analytics</b>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/AISoltani/Vison_advanced/refs/heads/main/RPA2.png" width="100%" alt="Vision-driven RPA"/><br/>
      <b>Vision-driven process automation</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/AISoltani/Vison_advanced/refs/heads/main/Safety.png" width="100%" alt="Site safety"/><br/>
      <b>Site safety: helmets, harnesses and restricted zones</b>
    </td>
    <td align="center" width="50%">
      <img src="https://raw.githubusercontent.com/AISoltani/Vison_advanced/refs/heads/main/TAS.png" width="100%" alt="Traffic analytics"/><br/>
      <b>Traffic analytics and vehicle tracking</b>
    </td>
  </tr>
</table>

---

## Strengths & Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,ts,kotlin,pytorch,tensorflow,opencv,sklearn,fastapi" alt="Languages and frameworks" />

<img src="https://skillicons.dev/icons?i=docker,aws,azure,git,github,linux,bash,raspberrypi,androidstudio" alt="Platforms and tooling" />

</div>

<p align="center">
  <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="100" alt="Animated cat coding" />
</p>

---

## Tech Stack

<p align="center">
  <img height="25em" src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" alt="Python" />
  <img height="25em" src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img height="25em" src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img height="25em" src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" alt="TensorFlow" />
  <img height="25em" src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white" alt="Keras" />
  <img height="25em" src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch" />
  <img height="25em" src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white" alt="OpenCV" />
  <img height="25em" src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn" />
  <img height="25em" src="https://img.shields.io/badge/mediapipe-0097A7.svg?style=for-the-badge&logo=mediapipe&logoColor=white" alt="MediaPipe" />
  <img height="25em" src="https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black" alt="Hugging Face" />
  <img height="25em" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" alt="Streamlit" />
  <img height="25em" src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
  <img height="25em" src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<p align="center">
  <img height="25em" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Kaggle" />
  <img height="25em" src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img height="25em" src="https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab" />
  <img height="25em" src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Azure" />
  <img height="25em" src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon AWS" />
  <img height="25em" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img height="25em" src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="Slack" />
</p>

<details>
<summary><b>Full stack</b></summary>

| Area | Tools |
|---|---|
| **Computer vision** | OpenCV, MMDetection, MONAI, MediaPipe, Ultralytics YOLO, SAM / SAM 2 / SAM 3, Albumentations |
| **Deep learning** | PyTorch, TensorFlow, Keras, scikit-learn, Hugging Face Transformers |
| **Foundation models and LLMs** | CLIP, DINOv2, SigLIP, Grounding DINO, LangChain, LangGraph, LlamaIndex, RAG, PEFT/LoRA |
| **Edge and deployment** | ONNX Runtime, TensorRT (INT8), TensorFlow Lite, NVIDIA DeepStream, Jetson Nano/Xavier/Orin, Raspberry Pi, Android/Kotlin |
| **Geospatial** | GDAL, Rasterio, GeoPandas, TorchGeo, SAHI, Sentinel Hub, rioxarray, Prithvi, Clay |
| **MLOps** | Docker, FastAPI, MLflow, Comet, Neptune, Weights & Biases, AWS, Azure |
| **Data and annotation** | CVAT, Labelbox, Roboflow, active-learning review |

</details>

---

## Certificates

> Each one links to its verification page.

<details>
<summary><b>AI in healthcare, machine learning and algorithms (16 certificates)</b></summary>

| Course | Provider | Credential |
|---|---|---|
| **AI in Healthcare Specialization** | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/specialization/R9C9W2YRK1WZ) |
| Introduction to Healthcare | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/MV4UYUOWYGTJ) |
| Introduction to Clinical Data | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/85BXCOE7ZWDI) |
| Fundamentals of Machine Learning for Healthcare | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/B1X7ZRZ7U7WY) |
| Evaluations of AI Applications in Healthcare | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/ZWEPEAF5WLJA) |
| AI in Healthcare Capstone | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/DN9UR5QS0Y3L) |
| Introduction to Medical Software | Yale University | [Verify](https://www.coursera.org/account/accomplishments/verify/64MM329IZ0NC) |
| Essentials of Global Health | Yale University | [Verify](https://www.coursera.org/account/accomplishments/verify/VDZZUE7065VT) |
| Breast Cancer | Yale University | [Verify](https://www.coursera.org/account/accomplishments/verify/DHYV19S7M35S) |
| **Machine Learning Specialization** | DeepLearning.AI and Stanford Online | [Verify](https://www.coursera.org/account/accomplishments/specialization/9YTCR5C6A57W) |
| Supervised Machine Learning: Regression and Classification | DeepLearning.AI and Stanford Online | [Verify](https://www.coursera.org/account/accomplishments/verify/U2S4BSCSTHK1) |
| Advanced Learning Algorithms | DeepLearning.AI and Stanford Online | [Verify](https://www.coursera.org/account/accomplishments/verify/H6OQV45C7N37) |
| Unsupervised Learning, Recommenders, Reinforcement Learning | DeepLearning.AI and Stanford Online | [Verify](https://www.coursera.org/account/accomplishments/verify/BYE5I5GSW96I) |
| Graph Search, Shortest Paths, and Data Structures | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/5S4RSTH8CABW) |
| Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming | Stanford University | [Verify](https://www.coursera.org/account/accomplishments/verify/LTDQ2550591R) |
| SmallTalk2 English Speaking Test | SmallTalk2 | [Verify](https://app.smalltalk2.me/cert/f7ddd517) |

</details>

---

## GitHub stats

<div align="center">

<a href="https://github.com/AISoltani"><img alt="AISoltani's GitHub stats" src="https://awesome-github-stats.azurewebsites.net/user-stats/AISoltani?cardType=level&theme=tokyonight&fontFamily=&preferLogin=false" /></a>

[![trophy](https://github-trophies.vercel.app/?username=AISoltani&theme=tokyonight&row=1&column=8)](https://github.com/AISoltani)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AISoltani/AISoltani/output/github-contribution-grid-snake-dark.svg">
  <img alt="Contribution grid snake animation" src="https://raw.githubusercontent.com/AISoltani/AISoltani/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

## Contact

<p align="center">
  <img src="https://raw.githubusercontent.com/ShahriarShafin/ShahriarShafin/main/Assets/handshake.gif" width="100" alt="Animated handshake" />
</p>

Open to senior Generative AI, LLMs, VLMs, computer vision and machine learning roles, research collaborations and PhD opportunities.

<p align="center">
  <a href="mailto:amirsoltani.os@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/amir-soltani-aisoltani/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://aisoltani.github.io"><img src="https://img.shields.io/badge/Portfolio-0a0a23?style=for-the-badge" alt="Portfolio"></a>
  <a href="https://www.kaggle.com/aisoltani"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle"></a>
  <a href="https://x.com/AISoltani"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a>
</p>

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=AISoltani.AISoltani" alt="visitors"/>
</div>
