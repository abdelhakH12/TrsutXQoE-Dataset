# 🎬 TrustXQoE Dataset

**TrustXQoE Dataset** is an end-to-end cross-layer HLS edge QoE/QoS dataset for trust-aware video streaming, zero-touch networking, edge selection, SDN-CDN systems, QoE prediction, QoS analysis, and explainable AI.

> 🚧 **Release status:** The full dataset, processed files, metadata, documentation, DOI, and public links will be available soon.

---

## 📌 Dataset Title

**TrustXQoE Dataset: An End-to-End Cross-Layer HLS Edge QoE/QoS Dataset for Trust-Aware Video Streaming**

---

## 👥 Authors

- **Abdelhak Heroucha** — `abdelhak.heroucha@u-pec.fr`
- **Abdul Karim Gizzini** — `abdul-karim.gizzini@u-pec.fr`
- **Thiago Abreu** — `thiago.wanderley-matos-de-abreu@u-pec.fr`
- **Abdelhamid Mellouk** — `mellouk@u-pec.fr`

---


## 🌐 Project Website

The project website is available here:

🔗 **Website:** https://abdelhakheroucha.github.io/TrustXQoE-Dataset/

---

## 🔎 Overview

The dataset was collected using a controlled edge video streaming testbed with:

- **1** origin/content server
- **8** edge nodes
- **9** concurrent HLS clients
- **10** video streaming sessions per user
- **0.5 s** sampling interval
- **58,000+** temporally aligned samples
- **~150 GB** full dataset size
- **MOS labels from 0 to 5**

TrustXQoE captures the complete video streaming delivery chain:

```text
Origin Server
   ↓
Backhaul Network
   ↓
Edge Server
   ↓
Access Network
   ↓
Client Video Player
   ↓
MOS / QoE Feedback
```

TrustXQoE combines synchronized measurements from the client side, edge side, origin server, access network, backhaul network, and human QoE evaluation.

For each user, the dataset includes more than one possible delivery path. The dataset records the **selected edge node** and the **selected path** for each streamed video.

---

## ⭐ Important Features

- End-to-end HLS video streaming dataset
- Cross-layer QoE/QoS measurements
- Client playback metrics
- HLS segment download metrics
- Playback events
- Edge server logs
- Origin server logs
- Access network QoS metrics
- Backhaul network QoS metrics
- Topology and path metadata
- Selected edge information
- Selected path information
- Human QoE / MOS labels
- Useful for trust-aware video streaming
- Useful for zero-touch networking
- Useful for edge selection and path selection
- Useful for explainable AI and network intelligence

---

## 🧠 What You Can Do With This Dataset

This dataset can be used for:

- QoE classification
- QoE forecasting
- MOS prediction
- QoS-to-QoE modeling
- Edge selection
- Path selection
- Trust-aware networking
- Zero-touch networking
- SDN-CDN optimization
- Adaptive video streaming
- Edge caching analysis
- Congestion analysis
- Anomaly detection
- Explainable AI for networking
- Root-cause analysis of QoE degradation
- Proactive streaming control
- Network performance prediction
- Video delivery optimization
- Multi-layer network intelligence
- AI-based edge orchestration


## 📊 Key Statistics

| Item | Value |
|---|---:|
| Full dataset size | ~150 GB |
| Temporally aligned samples | 58,000+ |
| Concurrent users / clients | 9 |
| Streaming sessions per user | 10 |
| Edge nodes | 8 |
| Origin/content server | 1 |
| Sampling interval | 0.5 s |
| MOS label range | 0–5 |

---

## 📦 Dataset Availability

| Resource | Status |
|---|---|
| Full dataset | Coming soon |
| Processed CSV files | Coming soon |
| Raw logs | Coming soon |
| PCAP files | Coming soon |
| Recordings | Coming soon |
| MOS labels | Coming soon |
| Metadata | Coming soon |
| DOI | Coming soon |

---

## 📜 License

This dataset is planned to be released under:

**Creative Commons Attribution 4.0 International — CC BY 4.0**

Under this license, users may share and adapt the dataset for research and educational purposes, provided that appropriate credit is given.

---

## 📬 Contact

For questions about the dataset, please contact:

**Abdelhak Heroucha**  
`abdelhak.heroucha@u-pec.fr`

---

## 🚧 Status

This repository is under active preparation.

The full dataset, processed files, metadata, documentation, DOI, and public download links will be available soon.
