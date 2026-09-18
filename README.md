# Amogh Vijay Shetty

**MEng Computer Science @ Cornell University** · Machine learning and computer vision

I build ML systems for scientific and industrial problems — segmentation and regression pipelines for physics research, retrieval models for satellite remote sensing, and real-time detection and tracking for production video. Three peer-reviewed publications, two in Elsevier journals.

📍 Ithaca, NY · 📧 [avs97@cornell.edu](mailto:avs97@cornell.edu) · 💼 [LinkedIn](https://linkedin.com/in/amoghv)

---

## Selected work

| Project | What it is | Stack |
|---|---|---|
| **[vapor-bubble-dynamics-ml](https://github.com/amoghshetty7436/vapor-bubble-dynamics-ml)** | Two-stage ML pipeline for vapor-bubble segmentation and parameter prediction in nucleate flow boiling. 7 architectures × 3 losses benchmarked; **0.982 validation IoU**. Novel divergence-theorem 3D reconstruction cuts equivalent-diameter error to **0.48%**. *Published in Applied Thermal Engineering and AI Thermal Fluids.* | PyTorch, DeepLabV3+, scikit-learn, SciPy |
| **[ftxgb-net-aerosol-retrieval](https://github.com/amoghshetty7436/ftxgb-net-aerosol-retrieval)** | Hybrid FT-Transformer + XGBoost framework retrieving four aerosol parameters simultaneously from MODIS over India. **R > 0.97** under 10-fold CV against 9 AERONET stations; lifts retrievals inside the expected-error envelope from **63.91% to 95.05%**, beating MODIS MAIAC and MOD04_3K. | PyTorch, XGBoost, SHAP, Google Earth Engine |
| **[baggage-tracking-reid](https://github.com/amoghshetty7436/baggage-tracking-reid)** | Real-time conveyor baggage pipeline: YOLOv8 + ByteTrack persistent tracking, a two-stage cascade for tagless-baggage detection, autoencoder anomaly detection, and TransReID cross-camera person re-identification. | YOLOv8, ByteTrack, TransReID, OpenCV |
| **[nutriscan](https://github.com/amoghshetty7436/nutriscan)** | Multimodal vision system screening for nutritional deficiency from eye, nail and dental images — **95.3% across 12 categories** on IBM Vision Models, deployed to Watson ML with Cloudant storage and an IBM LLM recommendation layer behind a Django interface. IBM Hackathon. | IBM Watson ML, TensorFlow, Django |

## Publications

- Mohd Moiz, **A. Shetty**, A. Srivastava. *Data-driven empirical correlation framework for full-cycle vapor bubble dynamics in nucleate flow boiling.* **Applied Thermal Engineering** 289 (2026) 129873. [DOI](https://doi.org/10.1016/j.applthermaleng.2026.129873)
- Mohd Moiz, **A. Shetty**, A. Srivastava. *Two-stage machine learning framework for investigating vapor bubble dynamics in nucleate flow boiling.* **AI Thermal Fluids** 5 (2026) 100031. [DOI](https://doi.org/10.1016/j.aitf.2026.100031)
- **A. Shetty**, Mohd Moiz, V. Hole, A. Srivastava. *Evaluation of Deep Learning Models for Vapor Bubble Segmentation in Nucleate Flow Boiling.* **IHMTC 2025**.

## Experience

**Research Intern — IIT Bombay** · Jan–Jun 2025 · *Prof. Atul Srivastava*
Two-stage segmentation and regression pipeline for vapor-bubble dynamics; divergence-theorem volume reconstruction; Differential Evolution correlation fitting over 4,772 samples. Three papers.

**AI Team Intern — Hungama Digital Media** · May–Jul 2026
In-house technical reviewer for an AI creator-intelligence platform built by an external team. Translated SRS requirements into testable validation criteria and verified multi-source artist metrics through SQL, BI dashboards and API integration checks. Reported to the Founder & MD.

**Machine Learning Intern — Cooper Compass** · Nov 2024 – Jan 2025
Real-time baggage tracking with YOLOv8 + ByteTrack; custom dataset curation for tagless and damaged baggage detection; multi-camera person Re-ID with TransReID validated on Market-1501.

## Education

**Cornell University** — MEng, Computer Science · Aug 2026 – May 2027
Computer Vision · Systems for Large-Scale ML · Software Engineering in the Era of ML · Robotics

**Sardar Patel Institute of Technology, Mumbai** — BTech, Computer Science & Engineering (Data Science) · 2026 · **CGPA 9.20/10**

## Toolkit

**Languages** Python · C++ · Java · SQL · JavaScript
**ML** PyTorch · TensorFlow · Keras · scikit-learn · XGBoost · Transformers · OpenCV · YOLOv8 · SHAP
**Data** NumPy · Pandas · Matplotlib · Seaborn · Tableau · Power BI
