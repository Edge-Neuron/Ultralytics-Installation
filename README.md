# Ultralytics-Installation
This repository provides a step-by-step guide and scripts to install and run Ultralytics YOLO (YOLOv8) on Raspberry Pi (tested on Raspberry Pi 3B+/4). It's optimized for lightweight inference. Whether you're using the Pi for object detection, face recognition, or smart camera projects, this repo helps you set up everything with ease.

# 🚀 Ultralytics YOLOv8 on Raspberry Pi 🥧

[![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-Supported-green?logo=raspberrypi)](https://www.raspberrypi.com/)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-blue?logo=python)](https://github.com/ultralytics/ultralytics)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Supported-red?logo=opencv)](https://opencv.org/)
[![Watch on YouTube](https://img.shields.io/badge/Watch%20Demo%20Video-%F0%9F%8E%A5-red?logo=youtube)](https://youtu.be/7xhL0uPimmo?si=PbJ1rfsLZGmakrUu)

A complete guide and working setup to install and run **Ultralytics YOLOv8** on your **Raspberry Pi 3B+/4** with either a **32-bit or 64-bit OS**. This repo helps you turn your Pi into a **low-power object detection system** using YOLOv8.

---

## 📸 Demo

[![Watch on YouTube](https://img.shields.io/badge/Watch%20Demo%20Video-%F0%9F%8E%A5-red?logo=youtube)](https://youtu.be/7xhL0uPimmo?si=PbJ1rfsLZGmakrUu)

*Real-time object detection using YOLOv8 on Raspberry Pi 3 Model B+ (1GB RAM)*

---

## 🧰 Features

- ✅ YOLOv8 ready with Ultralytics library  
- ✅ Tested on Raspberry Pi 3B+, 4 (32-bit & 64-bit OS)
- ✅ Lightweight PyTorch and OpenCV setup
- ✅ USB/CSI camera support
- ✅ Sample detection script included
- ✅ Optional: Coral TPU acceleration support (guide coming soon)

---

## 📦 Installation (Auto Script)

### 🛠️ Requirements

- Raspberry Pi 3B+ / 4 (Recommended: 4GB RAM)
- Raspberry Pi OS (Lite or Desktop, 32/64-bit)
- Python 3.9+

### 💡 Quick Setup

```bash
git clone https://github.com/Edge-Neuron/Ultralytics-Installation.git
cd Ultralytics-Installation
bash install.sh
python3 run_yolo.py
```
🎯 Use Cases
🚨 Real-time security surveillance

👀 Object and person detection

📦 Package detection for smart mailboxes

🤖 Robotics and automation vision tasks

🛒 Smart retail/counter monitoring

🧠 Tips & Suggestions

  ✅ For faster performance:
  Use imgsz=320 instead of 640 when calling YOLO to reduce load.
  Use smaller YOLOv8 variants like yolov8n.pt.

  ✅ Want to use Coral TPU?
  Stay tuned and Subscribe to our YT Channel for TPU setup guide which will be added soon for USB accelerator.

  ✅ Stream video?
  Integrate the code with Flask or MJPEG Streamer to live stream detections from the Pi camera.

🧩 Contributing
Feel free to open Issues or Pull Requests if:

  You want to add support for other models (e.g., YOLOv5)

  You’ve optimized for performance

  You want to contribute detection scripts for custom use cases

📄 License
This project is licensed under the MIT License. See the LICENSE file for more info.

🙌 Support
If you found this useful, consider giving a ⭐️ to support the project. You can also:

Watch the repo for future updates

Share it with your Raspberry Pi community

Link to it from your blog or project

