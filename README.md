
# 🚁 SkyRescue AI – Intelligent Disaster Response System

An advanced, real-time AI application designed to assist in **disaster rescue operations** by detecting survivors, analyzing environments, and providing actionable insights using cutting-edge computer vision models.

---

## 📌 Overview

SkyRescue AI is a smart rescue assistant built using **Python**, **Gradio**, and **Ultralytics YOLOv8**.  
It is designed to support emergency teams by combining:

- 🔍 Object Detection for survivors, vehicles, and hazards  
- 🏷️ Scene Classification for disaster environments  
- 🚁 Drone Image Analysis for aerial rescue missions  
- 🌐 Browser-based interface for quick deployment  

Unlike general AI tools, SkyRescue AI ensures **mission-focused, reliable, and real-time insights** for disaster response teams.

---

## 🚀 Features

- 📷 Upload or stream drone images (JPG, PNG, live feed)  
- 🟩 Automatic bounding boxes for detected survivors/objects  
- 🏷️ Labels with confidence scores  
- 🌄 Scene classification (collapsed buildings, floods, fires, etc.)  
- 🎚️ Adjustable confidence threshold slider  
- 📊 Detection summary with object-by-object breakdown  
- ⚡ Real-time YOLOv8 processing  
- 🌐 Runs in browser — no installation needed for end users  

---

## 🧠 System Architecture

SkyRescue AI follows a **3-layer hybrid architecture**:

1. **Object Detection Model (YOLOv8m)**  
   - Detects survivors, vehicles, and obstacles  
   - Provides bounding boxes + confidence scores  

2. **Scene Classification Model (YOLOv8n-cls)**  
   - Identifies disaster environment type  
   - Displays scene label on annotated image  

3. **Rescue Intelligence Layer**  
   - Filters non-relevant detections  
   - Prioritizes rescue-related insights  
   - Generates structured rescue reports  

---

## ⚙️ How It Works

```
Drone captures image
        ↓
Image processed via OpenCV
        ↓
YOLOv8 Detection Model scans for survivors/objects
        ↓
Bounding boxes + labels drawn
        ↓
YOLOv8 Classification Model identifies disaster scene
        ↓
Rescue Intelligence Layer generates summary
        ↓
Annotated image + rescue report returned to user
```

---

## 🌍 Real-World Applications

- 🚁 Drone-based disaster rescue  
- 🆘 Survivor detection in collapsed buildings  
- 🌊 Flood and fire scene analysis  
- 🚦 Emergency traffic monitoring  
- 🏥 Medical and scientific rescue imaging  

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Contributors

- **Padamata Poojitha** — Developer & Designer  

---

> *"Rescue faster, smarter, safer — powered by AI."* 🚁🤖  


