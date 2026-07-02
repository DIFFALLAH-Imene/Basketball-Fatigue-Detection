# 🏀 Intelligent Basketball Fatigue Detection System 🤖🧠

[![YOLOv8](https://img.shields.io/badge/Model-YOLOv8--Pose-purple.svg)](https://github.com/ultralytics/ultralytics)
[![Python](https://img.shields.io/badge/Language-Python%203.12-blue.svg)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/Library-OpenCV-green.svg)](https://opencv.org/)
[![Academic Project](https://img.shields.io/badge/Degree-Master%20Thesis-orange.svg)]()

An advanced computer vision and biomechanical analysis framework designed to detect physical fatigue in basketball players in real-time. By leveraging **YOLOv8-Pose estimation** and temporal tracking, the system extracts precise skeletal coordinates to compute ergonomic metrics, filtering out instant anomalies to deliver continuous fatigue monitoring.

---

## 🗺️ System Engineering Roadmap (Plan de Travail)

```mermaid
gantt
    title Framework Development Timeline
    dateFormat  YYYY-MM-DD
    
    section Phase 1: Data & Env
    Cloud & Library Setup             :done,    p1, 2026-07-01, 7d
    
    section Phase 2: Architecture
    YOLOv8-Pose Core Integration      :active,  p2, 2026-07-08, 10d
    
    section Phase 3: Biomechanics
    Law of Cosines Profiling          :         p3, 2026-07-18, 14d
    Spatial Normalization             :         p4, 2026-08-01, 7d
    
    section Phase 4: Temporal UI
    Multi-Entity Tracking             :         p5, 2026-08-08, 10d
    Dynamic Alert Overlay (OpenCV)    :         p6, 2026-08-18, 7d
