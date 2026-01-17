# Automated Car Accident Detection & Report Generation 🚗💥

This project implements an intelligent traffic surveillance system designed to detect vehicle accidents in real-time and automatically generate detailed incident reports using Deep Learning.

## 1. Project Overview
The system leverages computer vision to monitor traffic feeds, identify collisions, and provide immediate documentation for emergency services or insurance purposes.
* **Real-time Detection**: Uses fine-tuned YOLO models for high-speed accident identification.
* **Automated Reporting**: Integrates NLP to generate structured incident summaries based on visual data.
* **Surveillance Optimization**: Focused on detecting high-risk behaviors like motorcycle helmet violations and red-light jumping.

## 2. Methodology & Technical Stack
### Object Detection
* **Model**: YOLO (You Only Look Once) fine-tuned for accident-specific features.
* **Training**: Trained on high-quality surveillance footage and simulated accident scenarios.

### Preprocessing & Analysis
* **Frame Extraction**: Real-time processing of video streams for connected component analysis.
* **Feature Engineering**: Detection of vehicle speed anomalies and impact coordinates.



### Report Generation
* **NLP Integration**: Uses Large Language Models (LLMs) via the Groq API to convert detection metadata into human-readable reports.

## 3. Evaluation Metrics
The model is evaluated based on its ability to minimize false positives (e.g., sudden braking vs. actual collision) using:
* **Precision-Recall Curves**
* **mAP (mean Average Precision)**
* **Inference Speed (FPS)**

## 4. Installation
1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
