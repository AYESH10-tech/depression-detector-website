
# 🧠 Human-Centered Design for Ambient Assisted Living  
### 🎓 Final Year Project – Depression & Stress Detection for Elderly and Disabled People  
By **Ayesh Fernando** | BSc. Hons in Mechatronic Engineering

---

## 🔍 Project Overview

This project focuses on early **stress and depression detection** in elderly and disabled individuals through a human-centered, assistive technology approach. It combines:

- Real-time **emotion and motion detection** using computer vision  
- A **web-based interactive questionnaire** based on DSM-5 depression criteria  
- **Text input analysis** using NLP for emotional sentiment classification  
- Integration with **hardware components** such as Raspberry Pi Zero 2 W, NodeMCU, and USB webcams

---

## 📦 What's Included in This Repository

| File/Folder         | Description |
|---------------------|-------------|
| `index.html`        | Full website explaining the project (can be hosted with GitHub Pages) |
| `images/`           | Graphs and diagrams used in the website |
| `main.py`           | Python script for real-time webcam-based emotion tracking |
| `requirements.txt`  | Python dependencies for running the detection module |
| `report_generator.py` | (Optional) Module for generating automated health reports |
| `templates/`        | (If using Flask) HTML templates for dynamic rendering |
| `reports/`          | Folder where system-generated reports are saved |

---

## 🖥️ How to Run the Python Module

1. **Install Python 3.x** and ensure pip is available  
2. Open terminal in the project folder  
3. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the detection script:
   ```bash
   python main.py
   ```
5. The webcam will open and begin emotion/motion tracking  
6. Follow on-screen instructions and save or print your final report

---

## 🌐 How to Host the Website with GitHub Pages

1. Upload everything (not zipped) to your GitHub repo root  
2. Go to **Settings > Pages**  
3. Select:
   ```
   Branch: main
   Folder: / (root)
   ```
4. Save and open your live website at:  
   👉 `https://your-username.github.io/your-repo-name/`

---

## 🎯 Project Goals

- Assist mental health early detection in elder care environments  
- Develop a low-cost, deployable solution with real-time monitoring  
- Provide remote caregivers and doctors with automated reports  
- Support further development for Sinhala/Tamil versions

---

## 📚 References

- DSM-5 Depression Diagnostic Guidelines – APA  
- Multimodal AI for Health Monitoring – IEEE 2023  
- Facial Emotion AI – OpenCV & DeepFace  
- Sentiment Analysis in Healthcare – ACM 2022
