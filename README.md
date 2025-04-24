<h1 align="center">🚦 Traffic_Trade 🚀</h1>
<h3 align="center">An AI-Powered Smart Traffic Signal Management System Using YOLOv5 + ESP32</h3>

<p align="center">
  <img src="https://img.shields.io/github/stars/Gaurav-Gt01/Traffic_Trade?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/Gaurav-Gt01/Traffic_Trade?style=social" alt="Forks">
  <img src="https://img.shields.io/github/repo-size/Gaurav-Gt01/Traffic_Trade" alt="Repo Size">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome">
</p>

<p align="center">
  <b>A fusion of Artificial Intelligence, IoT, and Embedded Systems to make urban traffic smarter, faster, and future-ready.</b><br/>
  <i>Built with ❤️ at VJTI by Gaurav Tatpate</i>
</p>

---

## 🧠 About the Project

Urban traffic systems today still rely on **fixed-timer-based signals** that often create unnecessary congestion and delay. **Traffic_Trade** changes this by introducing:

> 🎯 A **YOLOv5-based real-time vehicle detection system** combined with an **ESP32-controlled traffic signal unit** that intelligently adjusts green signal durations based on actual vehicle count.

This is not just a simulation — it’s a **working prototype** built for real-world feasibility using **Computer Vision**, **Microcontrollers**, and a clean, modular **Python + Arduino** architecture.

---

## 💡 Key Highlights

✨ Real-time car & truck detection using **YOLOv5**  
🚥 Smart traffic light timing based on **vehicle density (10s–60s)**  
💡 Visual simulation using **ESP32 & LEDs on a breadboard**  
🔌 Plug & play logic for **video, image & webcam input**  
📈 Future-scope ready with options for **live camera feeds**, **cloud logging**, and **emergency vehicle detection**

---

## 🖼️ System Architecture

Traffic_Trade
├── input/                  # Input images or videos for testing  
├── output/                 # Outputs with detected vehicles + signal timings  
├── weights/                # YOLOv5 pretrained weights (.pt files)  
├── TD1.py                  # Image input + ESP32 control  
├── TD2.py                  # Live webcam feed integration  
├── TD3.py                  # Video file-based detection  
├── Traffic_Trade.ipynb     # Notebook for combined experiments  
├── FPupdated.ino           # Arduino code for ESP32 signal management   
├── requirements.txt        # Python dependencies   
└── README.md               # Project documentation (this file)   

## Developers 
[GAURAV TATPATE](https://github.com/Gaurav-Gt01)    
[KUSHAL BHAN ](https://github.com/kushalb005)
