# Ammara Noor

**AI engineer building visual inspection systems and intelligent workflows with Python, computer vision, and applied machine learning.**

BS Computer Engineering, NUTECH (2026). I build computer vision and Python AI projects end to end: data, model, evaluation, API and interface. Each project below states its numbers, how they were measured, and where they stop being valid.

[Portfolio](https://ammaranoor.vercel.app) · [Email](mailto:ammaran620@gmail.com) · [LinkedIn](https://linkedin.com/in/ammaranoorkhan)

## Featured projects

**[Fabric Defect Inspection](https://github.com/ammaran620-de/Febric-Defect)** ([live demo](https://ammaran620-de.github.io/Febric-Defect/))
YOLOv8n defect detection for textile images with a FastAPI service, an inspection log and a dashboard. F1 0.869 on its 80-image validation split, against 0.093 for an OpenCV baseline; there is no separate test set. The demo runs the model in your browser.

**[Industrial Anomaly Detection MLOps](https://github.com/ammaran620-de/industrial-anomaly-detection-mlops)**
PatchCore detector trained on defect-free images only, served with FastAPI and tracked in MLflow. Image AUROC 0.9956 on MVTec AD carpet (coreset ratio 0.05, 320 px). The README documents the score overlap behind the four errors, that the threshold is set on the test images, and that latency has not been measured.

**[SiteSignal Delay Intelligence](https://github.com/ammaran620-de/sitesignal-delay-intelligence)**
Construction delay analysis on synthetic project data. A deterministic critical-path engine does the schedule maths and is tested without any model; an LLM agent selects tools and explains the results (it needs your own Gemini API key).

**[Ayah Feedback Lab](https://github.com/ammaran620-de/ayah-feedback-lab)**
Research prototype: can a speech model get every word right and still miss a pronunciation error? Whisper wording check plus an acoustic classifier on two ayahs, evaluated on 144 held-out clips with its false flags shown. Not a teaching tool.

## More work

- [EHR Review Desk](https://github.com/ammaran620-de/ehr-review-desk): Streamlit dashboard that flags unusual access patterns in synthetic health-record data with Isolation Forest and SHAP. Synthetic data only.
- [Harvest Web Scraper](https://github.com/ammaran620-de/harvest-web-scraper): a scraper that traces each record back to its source page.
- [Radar Loop Study](https://github.com/ammaran620-de/radar-loop-study): research study validating loop-closure candidates on public radar data, using the authors' frozen RadarLoc checkpoint.
- [Foundry](https://github.com/ammaran620-de/foundry): recorded CPU and integrated-GPU benchmarks for YOLO26n across PyTorch, ONNX Runtime and OpenVINO, plus a local in-browser WebGPU build.

## Skills used in these repositories

Python, PyTorch, Ultralytics YOLO, OpenCV, scikit-learn, ONNX Runtime, FastAPI, Streamlit, MLflow, SQLite, pytest, Docker, GitHub Actions.

## Get in touch

Email or LinkedIn, as linked at the top.
