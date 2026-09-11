UrbanSense 🚍🏙️

AI-Powered Mobile Urban Intelligence Platform Using Public Transport Fleets

UrbanSense turns public transport buses into mobile urban sensing units to detect and analyze road conditions, traffic, hazards, and infrastructure issues across a city.

🚦 What It Does

Bus Camera + GPS
        ↓
AI Detection
        ↓
Geolocation
        ↓
Multi-Bus Verification
        ↓
Urban Intelligence
        ↓
Authority Action + Public Alerts

⭐ Key Features

🚌 Mobile Urban Sensing using public buses

🤖 AI-based Road & Traffic Detection

📍 GPS + GIS Intelligence

🔄 Multi-Bus Verification to confirm persistent issues

🚧 Road Blockage & Hazard Detection

📊 Traffic Intelligence & Road Health

🔔 Road User Alerts

🌀 CurveSense for curve-aware trajectory and road-risk analysis

🏛️ Authority Dashboard & Reporting

🌀 CurveSense

CurveSense analyzes how vehicles interact with road curves by comparing ideal and observed trajectories.

It provides indicators such as:

Curve Risk Score

Apex Deviation

Speed Reduction

Braking Behaviour

Multi-Bus Observations

Priority Level

Note: CurveSense values in the current prototype are simulated demonstration data.

🧠 Technology Stack

Layer

Technologies

Data Collection

Camera, GPS, IMU

AI / CV

Python, YOLO, OpenCV

Backend

FastAPI

Database

PostgreSQL, PostGIS

GIS

OpenStreetMap, MapLibre

Frontend

React, Vite, Tailwind CSS

Deployment

Docker, Cloud / Edge

🖥️ Prototype

The current MVP includes:

User Portal

Traffic maps

Road hazards and blockages

Road-user alerts

CurveSense safety information

Authority Portal

City overview

Live simulated bus fleet

AI detections

Multi-bus verification

Traffic intelligence

Urban issue management

Road Health Index

CurveSense

Authority reports

☁️ Architecture

UrbanSense follows a hybrid Edge + Cloud architecture.

Camera / GPS / IMU
        ↓
     Edge AI
        ↓
Evidence + Event Metadata
        ↓
 Cloud / Central Platform
        ↓
PostgreSQL + PostGIS
        ↓
 GIS Dashboard
        ↓
Authority / User Portal

🎬 Demo Mode

The current prototype uses simulated fleet telemetry, detections, GPS data, traffic data, and CurveSense measurements to demonstrate the complete workflow.

It is a prototype and not a live municipal deployment.

🚀 Future Scope

Hit-and-Run Case Detection
Detect suspicious vehicle incidents and support identification using video evidence and vehicle tracking.

Blind-Spot Detection
Identify vehicles or road users entering high-risk blind-spot areas.

Near-Miss Detection & Accident Hotspot Identification
Detect dangerous near-miss events and analyze repeated incidents to identify accident-prone hotspots.

Smart Roads. Safer Cities. 🚍

UrbanSense | SIH 2026
