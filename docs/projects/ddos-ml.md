# DNS DDoS (ML + Graylog)

**Goal:** Detect amplified DNS flows in near real-time and visualize alerts.

**Stack:** Python (scikit-learn), FastAPI, GELF → Graylog, Ubuntu 24.04

## Architecture
- CICFlowMeter / tcpdump → feature vectors
- RandomForest/XGBoost → prediction
- FastAPI → inference + GELF → Graylog
- Dashboards → detection widgets + timelines

## Results (Test Set)
- Accuracy ~99.99%, very low FPR
- <2s detection-to-alert latency (lab)
