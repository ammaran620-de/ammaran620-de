# Ammara Noor

**AI engineer building visual inspection systems and intelligent workflows with Python, computer vision, and applied machine learning.**

BS Computer Engineering, NUTECH (2026). I build computer vision and Python AI projects end to end: data, model, evaluation, API and interface. Each project below states its numbers, how they were measured, and where they stop being valid.

[Portfolio](https://ammaranoor.vercel.app) · [Email](mailto:ammaran620@gmail.com) · [LinkedIn](https://linkedin.com/in/ammaranoorkhan)

## Public prototypes

**[Fabric Defect Inspection](https://github.com/ammaran620-de/Febric-Defect)** ([live demo](https://ammaran620-de.github.io/Febric-Defect/))
YOLOv8n defect detection for textile images with a FastAPI service, an inspection log and a dashboard. On its 80-image validation split, class-agnostic F1 is 0.869 (a box counts if it overlaps a labelled defect) against 0.093 for an OpenCV baseline, and class-aware F1 is 0.848. There is no separate test set. The demo runs the model in your browser.

**[SiteSignal Delay Intelligence](https://github.com/ammaran620-de/sitesignal-delay-intelligence)**
Construction delay analysis on synthetic project data. A deterministic critical-path engine does the schedule maths and is tested without any model; an LLM agent selects tools and explains the results, and its citations are checked against what the tools returned. The 80 tests use a scripted stand-in for Gemini, so they do not show that the live model answers well. It needs your own Gemini API key.

**[EHR Review Desk](https://github.com/ammaran620-de/ehr-review-desk)**
Streamlit dashboard that flags unusual access patterns in synthetic health-record data with Isolation Forest and SHAP. Synthetic data only.

## Recorded benchmarks and research

**[Industrial Anomaly Detection MLOps](https://github.com/ammaran620-de/industrial-anomaly-detection-mlops)**
PatchCore detector trained on defect-free images only, served with FastAPI and tracked in MLflow. The recorded run on MVTec AD carpet reached image AUROC 0.9956 (coreset ratio 0.05, 320 px), with its threshold taken from the test set's own good images. The code now validates checkpoints on load, seeds training and calibrates the threshold on held-out normal training images; the recorded run has not been repeated with that change, and the README keeps the original figures labelled as historical. Latency has not been measured.

**[Foundry](https://github.com/ammaran620-de/foundry)**
Recorded CPU and integrated-GPU benchmarks for YOLO26n across PyTorch, ONNX Runtime and OpenVINO, a regression gate with unit tests (run on Linux, Windows and macOS in CI), and a local in-browser WebGPU build. The accuracy gap between PyTorch and the exported runtimes is documented, not explained.

**[Ayah Feedback Lab](https://github.com/ammaran620-de/ayah-feedback-lab)**
Research prototype: can a speech model get every word right and still miss a pronunciation error? Whisper wording check plus an acoustic classifier on two ayahs, evaluated on 144 held-out clips with its false flags shown. Not a teaching tool.

**[Radar Loop Study](https://github.com/ammaran620-de/radar-loop-study)**
Study validating loop-closure candidates on public radar data, using the authors' frozen RadarLoc checkpoint.

## Other

- [Harvest Web Scraper](https://github.com/ammaran620-de/harvest-web-scraper): a scraper that traces each record back to its source page.

## Professional work (not in these repositories)

- AI and Computer Vision Engineer, Robionix Technologies, part-time, 2024 to 2026: labelled mill-floor images, trained YOLOv8 on three defect classes and tuned thresholds after reviewing false positives.
- Full-Stack AI Developer, Evolvian Softwares, August 2025 to January 2026: document-review endpoints and dashboards.
- AI and UAV Engineering Intern, National Development Complex, July to September 2025: person tracking and vehicle detection.
- MagicQC, a garment-measurement workflow, is proprietary and under NDA. No code, data or results from it appear in my public repositories.

## Skills used in these repositories

Python, PyTorch, Ultralytics YOLO, OpenCV, scikit-learn, ONNX Runtime, FastAPI, Streamlit, MLflow, SQLite, pytest, Docker, GitHub Actions.

## Get in touch

Email or LinkedIn, as linked at the top.
