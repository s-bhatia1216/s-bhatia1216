## 👋 Hi there, I'm Sonal!
## 🚀 About Me

#### I'm an aspiring **AI/ML Engineer** with skills spanning across scientific programming in Python, software development in Java and C++, and a keen interest in the intersections of AI/ML, performance analysis, robotics, and aerospace. 
#### From January - August 2025 & June - August 2026, I worked as an AI Intern in the System Performance Architecture group within Hardware Engineering at Apple Inc. My opinions, repos and other content here are not a reflection of my employers, unless otherwise specified or agreed. I am making my contributions/submissions to the projects in my personal capacity and am not conveying any rights to any intellectual property of any third parties.
### 🔗 [LinkedIn](https://www.linkedin.com/in/sbhatia1216)

---
## 🛠️ Some of My Projects

### 🌌 [constellation-analyzer](https://github.com/s-bhatia1216/constellation-analyzer)
*Interactive LEO constellation simulation for assessing a 1 GW space-based data center — Built for MAE 426*
- **Overview:** A browser-based orbital mechanics simulator for designing and analyzing low Earth orbit satellite constellations. Explores the architecture behind a 1 GW solar-powered space data center by letting users tune constellation parameters and see real-time coverage, gap, and power metrics.
- **Technologies:** Three.js r128, Vanilla HTML/CSS/JS (no build step, no dependencies)
- **Features:** Live orbital simulation with adjustable planes, inclination, altitude, and phase offset; Starlink/OneWeb/Polar presets; coverage %, gap time, orbital period, and footprint area metrics computed client-side.

---

### 🚂 [Mt. Rainier Railroad — Bench 5](https://github.com/s-bhatia1216/mt-rainier-railroad)
*Autonomous track switching, obstacle detection, and train control — MAE 412 Capstone*
- **Overview:** An embedded systems capstone simulating a segment of the Mount Rainier Scenic Railroad. The Vector Board Arduino autonomously manages track switches, detects fallen tree obstacles via ToF sensors, and forwards DCC speed/direction commands through a Python passthrough to a command station.
- **Technologies:** Arduino (C++), Python (serial bridge), VL53L0X ToF sensors (I2C), ACIA/SoftwareSerial, DCC, Fusion 360
- **Features:** Timed 3-pattern switch cycling triggered by train occupancy detection, dual-sensor obstacle detection with automatic track power cutoff, randomized servo-driven scenery animation, assembly firmware for signal sensor board.

---

### 🚶 [pedestrian-detection](https://github.com/s-bhatia1216/pedestrian-detection)
*Benchmarking HOG, Faster R-CNN, DETR, and SAM2 on the PnPLO Pedestrian Dataset — Princeton University*
- **Overview:** A controlled architecture-level comparison of four pedestrian detection paradigms evaluated on the PnPLO (Person vs. Person-Like Objects) dataset, focusing on robustness to false positives from statues, mannequins, and other visually similar non-pedestrians.
- **Technologies:** Python, PyTorch, torchvision, OpenCV, NumPy, Matplotlib, Seaborn, Google Colab
- **Features:** Unified evaluation pipeline with precision, recall, F1, mAP, false positive breakdowns, PR curves, and confusion matrices across HOG+SVM, Faster R-CNN, DETR, and YOLO+SAM2.
- **📄 [View Full Report](written_report.pdf)**

---

### 📐 [Shap-E](https://github.com/s-bhatia1216/shap-e/tree/mps-support)
*APPLE: Enabling Shap-E to run on Apple Silicon GPUs via Metal Performance Shaders (MPS) Acceleration*
- **Overview:** Shap-E falls back to CPU on Apple M-series machines because certain indexing ops are not yet supported by PyTorch-MPS. This PR removes that blocker, giving native-GPU performance on macOS without sacrificing CUDA/CPU compatibility.
- **Technologies:** Python, PyTorch MPS
- **Features:** Significant performance increase while running Shap-E locally on Mac M-series, for example, on a Mac mini (M4 Pro), default image-to-3D generation time drops from 4 hours to just under 4 minutes when switching from CPU to GPU via MPS.
- **📄 [View Pull Request](https://github.com/openai/shap-e/pull/159)**

---

### 📈 [StockSwipe](https://github.com/s-bhatia1216/stockswipe)
*Tinder-style stock discovery powered by Claude AI — Built for the AI@Princeton x Trade[XYZ] Hackathon*
- **Overview:** A mobile-first investing experience where users swipe right to invest and left to skip, with flippable cards showing live AI analysis, real-time news, and interactive charts.
- **Technologies:** React 18, Vite, Framer Motion, Express (Node.js), Anthropic SDK (Claude Haiku + Sonnet), Yahoo Finance, Finnhub API, YouTube Data API
- **Features:** Physics-based swipe gestures, Claude-generated stock hooks, AI portfolio analysis with Risk Radar, gamified streaks & badges, social friends feed & leaderboard, vertical Reels feed.
- **🎥 [Watch Demo](https://youtube.com/shorts/up3gJdMNWNM?feature=share)**

---

### 💊 [NANI](https://github.com/s-bhatia1216/nani)
*An AI-powered compassionate medicine companion for elderly patients — Built for HackPrinceton F25*
- **Overview:** NANI ("grandmother" in Hindi) is a full-stack IoT medication adherence system that uses IR beam sensors to passively detect when medication is taken and a voice-first AI assistant to answer health questions in multiple languages — keeping patients independent while keeping families informed.
- **Technologies:** Raspberry Pi (Python, FastAPI), Node.js (Express, OpenAI Whisper/GPT-4o-mini/TTS), Swift (iOS), Google Sheets (data logging)
- **Features:** Passive IR beam medication detection, bilingual voice assistant (English/Hindi), real-time Care Circle notifications for family and caregivers, cultural sensitivity, automatic adherence tracking.
- **🎥 [Watch Demo](https://youtu.be/y7C8Kh3Aam4)**

---

### 💄 [Unwrapping Customer Delight](https://github.com/s-bhatia1216/unwrapping-customer-delight)
*Using Frequentist and Bayesian Regression Models to Optimize Surprise Gift Strategies*
- **Overview:** Developed a Bayesian Regression Discontinuity Design to evaluate and optimize the return on investment of surprise gift campaigns.
- **Technologies:** Python, NumPyro, Pandas, Jax, StatsModels, Matplotlib
- **Features:** Data Visualization & Actionable Insights.
- **📄 [View Project README](https://github.com/s-bhatia1216/unwrapping-customer-delight/blob/main/README.md)**

---

### 🏠 [airbnbpriceprediction](https://github.com/s-bhatia1216/airbnbpriceprediction)
*Predicting Airbnb listing prices in New York City using various regression models.*
- **Overview:** Developed models to predict Airbnb prices, with the Random Forest model showing the best performance.
- **Technologies:** Python, Jupyter Notebook, Scikit-learn, Pandas, Numpy, Seaborn
- **Features:** Data preprocessing, model training, evaluation metrics.
- **📄 [View Project README](https://github.com/s-bhatia1216/airbnbpriceprediction/blob/main/README.md)**

---

### 🕺 [naacho-website](https://github.com/s-bhatia1216/naacho-website)
*Modern and responsive website for Naacho Dance Company at Princeton.*
- **Overview:** Features event details, member bios, and integrated Google Maps for location information.
- **Technologies:** HTML, CSS, Bootstrap
- **Features:** Responsive design, interactive elements, user-friendly interface.
- **📄 [View Project README](https://github.com/s-bhatia1216/naacho-website/blob/main/README.md)**

---

### 🧠 [neuroboost POC](https://github.com/s-bhatia1216/neuroboost)
*Implementing CNNs and RNNs to analyze and predict trends in cognitive function.*
- **Overview:** Proof of concept utilizing deep learning models for cognitive trend analysis.
- **Technologies:** Python, TensorFlow, Keras
- **Features:** Model implementation, data analysis, prediction visualization.
- **📄 [View Project README](https://github.com/s-bhatia1216/neuroboost/blob/main/README.md)**

---

## 📫 Connect with Me
- [LinkedIn](https://www.linkedin.com/in/sbhatia1216) 🔗
- [Email](mailto:sbhatia1216@gmail.com) 📧
---
✨ Thank you for visiting my profile! Let's build something amazing together. 🚀
