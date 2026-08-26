<h1 align="center">Ammara Noor</h1>

<p align="center">
  <b>Computer Vision Engineer</b><br>
  I ship vision systems that run on live cameras — not just in notebooks.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=yolo&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

<p align="center">
  <a href="mailto:ammaran620@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/ammaranoorkhan"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Lahore,_Pakistan-333?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Open_to_work-0E9E70?style=flat-square" />
</p>

---

### What I actually do

Take a model from **on-site data collection** → **training** → **evaluation you can defend** → **REST API and dashboard**. My defect-detection work runs on live camera input inside a working textile mill, and I have collected and labelled the data myself, on the factory floor, at 6am.

Currently deepening **C++ and edge inference** — getting models onto constrained hardware.

---

## Featured project

### [Industrial Anomaly Detection — MLOps Pipeline](https://github.com/ammaran620-de/industrial-anomaly-detection-mlops)

**A defect detector that never sees a defect during training.**

Supervised inspection only finds defects you thought to label. On a real line, the dangerous ones are the ones nobody has seen. So this learns what *normal* looks like — frozen CNN, patch-level memory bank, greedy k-center coreset kept at 1% — and flags anything far from it.

| Metric | Result |
|:---|:---|
| Image AUROC | **0.9956** |
| Precision / recall / F1 | 0.9775 |
| Accuracy | 0.9658 |
| Confusion | 87 caught · 26 passed · 2 missed · 2 false alarms |
| Inference | 535 ms / image on CPU |
| Dataset | MVTec AD carpet, 117 test images |

**What the number hides.** All four errors sit in a narrow score band, 2.02–2.19. Below it, defects are indistinguishable from high-variance normal carpet; above it, separation is clean. One colour defect cleared the 2.1189 threshold by 0.00004 — recall of 0.9775 rests on that margin. The distributions genuinely overlap, so no threshold fixes it. That overlap is why AUROC is 0.9956 and not 1.0.

**What it does not do.** 535 ms per image does not meet the 33 ms a 30 fps line requires. Documented under limitations with the optimisation path — ONNX export, INT8 quantisation, coreset reduction — rather than quietly omitted.

`PatchCore` `PyTorch` `MLflow` `FastAPI` `Docker` `pytest` `GitHub Actions`

---

## Experience

**Computer Vision Engineer** (part-time) · Robionix Technologies · *Feb – Jun 2026*
Built **MagicQC**, pairing YOLOv8 detection with PatchCore anomaly detection so known *and* unseen defect types are caught by one pipeline. ~1,600 images self-collected on-site at a textile mill; 95% accuracy on a held-out test split across 3 defect classes. Full path from camera capture to React alert dashboard. Exhibited at the **32nd Textile Asia Expo, Lahore** — evaluation interest from Nishat Mills, Gul Ahmed and Sapphire.

**Full-Stack AI Developer** · Evolvian Softwares · *Aug 2025 – Jan 2026*
YOLOv8, OCR and RAG pipelines integrated into client-facing production web applications.

**AI and UAV Intern** · NDC, NESCOM · *Jul – Sep 2025*
Person tracking and vehicle detection on live aerial video — moving camera, changing light, real-time constraints.

---

## Toolkit

| | |
|:---|:---|
| **Vision** | Object detection · segmentation · anomaly detection · OCR · tracking · real-time video |
| **ML** | PyTorch · TensorFlow · OpenCV · Ultralytics · scikit-learn · NumPy |
| **ML engineering** | MLflow · FastAPI · ONNX · Docker · pytest · latency profiling |
| **Languages** | Python · JavaScript · SQL · C/C++ |
| **Full-stack** | React · Next.js · Node.js · REST APIs · MySQL |
| **Hardware** | GigE Vision & line-scan cameras · OAK depth cameras |

---

## Background

**BS Computer Engineering** — NUTECH Islamabad, 2026

🥇 **1st Place** — ICAT National Robotics Competition 2025
🎓 **Millennium Fellow** — UN Academic Impact Program
👩‍💻 **Chair** — IEEE Women in Engineering, NUTECH

---

<p align="center"><i>Open to computer vision and ML engineering roles — Lahore, Islamabad, Karachi or remote.</i></p>
