# UrbanSense AI

**Turning Public Transit Fleets into Distributed Urban Sensing Networks**

![Deployment Mode](https://img.shields.io/badge/Mode-Demo%20%2F%20Simulated%20Data-amber)
![Hackathon](https://img.shields.io/badge/SIH-2026-teal)
![PS Code](https://img.shields.io/badge/Problem%20Statement-SIH26124%20(BEL)-blue)
![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-14b8a6)

UrbanSense AI is a smart-city operations platform designed for municipal corporations and transit authorities. It transforms existing municipal bus fleets into rolling road-quality and traffic sensors using forward-facing camera feeds, lightweight edge detection, spatial consensus verification, and automated work-order dispatch.

---

## The Problem & The Solution

* **The Problem:** Municipalities rely on delayed citizen grievances or expensive, dedicated survey vehicles to track road decay and bottlenecks.
* **The UrbanSense Approach:** City buses traverse high-density corridors multiple times daily. UrbanSense AI processes dashcam streams locally on the vehicle, transmitting only lightweight telemetry metadata (GPS, defect classification, bounding box coordinates, and confidence) to a central municipal command dashboard.

```text
BUS CAMERA
   ↓
AI DETECTION (Edge INT8 Inference)
   ↓
GEO-TAGGED OBSERVATION
   ↓
MULTI-BUS VERIFICATION (Consensus Deduplication)
   ↓
URBAN INTELLIGENCE (Traffic & Road Health Impact)
   ↓
AUTHORITY REPORT & CONNECTED DRIVER WARNINGS
