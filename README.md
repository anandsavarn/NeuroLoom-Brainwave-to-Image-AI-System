<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0021,50:1a0050,100:4a0080&height=220&section=header&text=NeuroLoom&fontSize=60&fontColor=cc88ff&fontAlignY=36&desc=Brainwave-to-Image%20AI%20System%20%7C%20EEG%20%E2%86%92%20Digital%20Art&descAlignY=58&descColor=e0b3ff&animation=fadeIn" width="100%"/>

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenBCI](https://img.shields.io/badge/OpenBCI-EEG%20Hardware-8A2BE2?style=for-the-badge)
![GANs](https://img.shields.io/badge/GANs-Generative%20AI-blueviolet?style=for-the-badge)
![Neural Style Transfer](https://img.shields.io/badge/Neural%20Style%20Transfer-AI%20Art-ff69b4?style=for-the-badge)
![VR/AR](https://img.shields.io/badge/VR%20%2F%20AR-Immersive-00bcd4?style=for-the-badge)

<br/>

> **NeuroLoom transforms real-time brainwave signals (EEG) into dynamic, ever-evolving digital artwork using AI — bridging neuroscience, generative art, and human creativity.**

<br/>

![Status](https://img.shields.io/badge/Status-Prototype%20In%20Development-yellow?style=for-the-badge)
![Patent](https://img.shields.io/badge/IPR-Patent%20Filed%20(LPU)-green?style=for-the-badge)
![Institution](https://img.shields.io/badge/Institution-Lovely%20Professional%20University-orange?style=for-the-badge)

<br/>

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-anandsavarn.vercel.app-00C896?style=for-the-badge)](https://anandsavarn.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Anandsavran-181717?style=for-the-badge&logo=github)](https://github.com/Anandsavran)

</div>

---

## 🧠 What Is NeuroLoom?

**NeuroLoom** is a patent-filed AI system that reads your brain's electrical activity in real-time using an EEG headset and converts those signals into beautiful, continuously evolving digital art.

When you're **relaxed** → soft, fluid visuals in calming blues.
When you're **focused** → sharp, dynamic patterns in energetic reds.
When you're **creative** → abstract, flowing generative art.

No art skills needed. No commands to type. Just think — and watch your mind become art.

> 🏛️ **This project is a filed invention disclosure at Lovely Professional University, Punjab, India — submitted for complete patent filing (PCT).**

---

## 👥 Inventors

| Name | UID | Institution |
|---|---|---|
| **Anand Kumar** | 12320597 | Lovely Professional University |
| Kaushal Kishor | 12312824 | Lovely Professional University |
| Ashwini Kumar | 12308859 | Lovely Professional University |

---

## 🚨 Problem We're Solving

Current EEG / brain-computer interface (BCI) systems are either:
- 🏥 **Too clinical** — showing raw waveforms, heatmaps, and charts only experts understand
- 🎨 **Disconnected from creativity** — AI art tools don't interact with real-time bio-signals

**NeuroLoom fills this gap** — making your brain activity visible, personal, and beautiful, with zero technical knowledge required.

---

## 🔄 How It Works — System Pipeline

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│  1. EEG DATA ACQUISITION                                        │
│     EEG Headset (OpenBCI / Muse / Emotiv)                       │
│     Captures: Delta, Theta, Alpha, Beta, Gamma waves            │
│                          │                                      │
│                          ▼                                      │
│  2. SIGNAL PREPROCESSING                                        │
│     • Noise Reduction & Artifact Removal                        │
│     • FFT / Wavelet Transform / ICA Filtering                   │
│     • Power Spectral Density (PSD) Analysis                     │
│                          │                                      │
│                          ▼                                      │
│  3. FEATURE EXTRACTION & COGNITIVE CLASSIFICATION               │
│     • Brainwave band analysis                                   │
│     • ML Models: SVM, k-NN, Deep Neural Networks (DNN)          │
│     • Output: Mental state label (Relaxed / Focused / Creative) │
│                          │                                      │
│                          ▼                                      │
│  4. AI-BASED ART GENERATION                                     │
│     • GANs (Generative Adversarial Networks)                    │
│     • Neural Style Transfer (NST)                               │
│     • Visual Parameter Mapping (color, stroke, speed)           │
│                          │                                      │
│                          ▼                                      │
│  5. USER INTERFACE & INTERACTION                                 │
│     • Style selection, parameter adjustment                     │
│     • Real-time EEG feedback display                            │
│                          │                                      │
│                          ▼                                      │
│  6. OUTPUT / DISPLAY                                            │
│     Screens • VR/AR Headsets • LED Walls • Projections          │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🎨 Brainwave → Art Mapping

| Brainwave | Frequency | Mental State | Visual Output |
|---|---|---|---|
| **Delta** | 0.5–4 Hz | Deep sleep | Slow, dark, flowing shapes |
| **Theta** | 4–8 Hz | Meditation / Creativity | Dream-like, abstract patterns |
| **Alpha** | 8–14 Hz | Relaxed / Calm | Soft blues, smooth fluid motion |
| **Beta** | 14–30 Hz | Focused / Alert | Sharp lines, energetic reds |
| **Gamma** | 30–100 Hz | High Excitement | Fast-moving, bright, chaotic art |

---

## ⚙️ Tech Stack

```
🧠 EEG Hardware      →  OpenBCI, Muse, Emotiv Insight, NeuroSky
🐍 Language          →  Python
🤖 AI / ML           →  GANs, Neural Style Transfer, VAEs, Diffusion Models
📊 Signal Processing →  FFT, Wavelet Transform, ICA, PSD
🧮 ML Classification →  SVM, k-NN, Deep Neural Networks (DNN)
🖼️ Visualization     →  Matplotlib, OpenCV, Custom rendering engine
🥽 Immersive Output  →  VR / AR integration (planned)
🗄️ Data Pipeline     →  LSTM-based contrastive learning (EEG → latent space → image)
```

---

## 🏗️ System Architecture — 3 Core Modules

### Module 1 — EEG Data Acquisition
- Compatible with **OpenBCI, Muse, Emotiv** (4 to 64+ electrode support)
- Wireless transmission of raw brainwave signals
- Captures all 5 frequency bands simultaneously

### Module 2 — Signal Processing & Cognitive Analysis
```python
# Pipeline applied to raw EEG signal:
Step 1: Bandpass filtering (remove noise outside 0.5–100 Hz)
Step 2: Artifact rejection (eye blink, muscle movement removal via ICA)
Step 3: FFT / Wavelet decomposition into frequency bands
Step 4: Feature vector extraction (PSD per band)
Step 5: ML classifier → outputs mental state label
```

### Module 3 — AI-Driven Art Generation
- **GANs** — generate novel artwork conditioned on mental state
- **Neural Style Transfer (NST)** — apply artistic styles based on brainwave energy
- **Visual Parameter Mapping:**

```
Relaxed (Alpha dominant)  →  Color: Blues/Greens  | Stroke: Fluid  | Speed: Slow
Focused (Beta dominant)   →  Color: Reds/Yellows  | Stroke: Sharp  | Speed: Fast
Creative (Theta dominant) →  Color: Purples/Pinks | Stroke: Abstract| Speed: Medium
```

---

## 🔬 Research Foundation

This system is built on and validated against 3 existing patent gaps:

| Patent | Existing System | Gap | NeuroLoom's Novelty |
|---|---|---|---|
| US20150310688A1 | BCI for device control & neurofeedback | No artistic visualization | Real-time EEG → personalized generative art |
| US20170249958A1 | EEG meditation tools with graphs | Feedback only via charts | AI-powered neuroaesthetic art experiences |
| US20200312632A1 | Clinical EEG acquisition & analysis | Diagnostics only | Creative, therapeutic, immersive digital art |

---

## 🎯 Key Features

```
✔ Real-time EEG signal acquisition & processing
✔ AI-generated art that updates live with your brain activity
✔ Supports OpenBCI, Muse, Emotiv, NeuroSky hardware
✔ 5 brainwave bands → mapped to visual parameters
✔ GAN + Neural Style Transfer art engine
✔ Interactive UI — choose styles, themes, adjust parameters
✔ VR/AR compatible output
✔ Modular architecture — swap hardware or AI models easily
✔ Therapeutic applications — stress, ADHD, anxiety, mindfulness
✔ Multi-user collaborative art (roadmap)
```

---

## 🩺 Applications

| Domain | Use Case |
|---|---|
| 🎨 **Digital Art** | Artists create live brainwave-driven visual pieces |
| 🧘 **Mental Wellness** | Visualize and regulate stress, anxiety, emotional state |
| 🏥 **Therapy** | Neurofeedback for ADHD, PTSD, anxiety management |
| 🎓 **Education** | Interactive neuroscience — see brainwaves in real-time |
| 🥽 **VR/AR** | Step inside immersive 3D worlds shaped by your thoughts |
| 🎭 **Live Performances** | Audiences experience real-time collective neuro-art |
| 🔬 **Research** | Brain-to-image pipeline for cognitive science studies |

---

## 🧪 Current Prototype Status

| Component | Status |
|---|---|
| EEG Hardware Integration (OpenBCI + Muse) | ✅ Ready & Tested |
| Signal Processing Pipeline (FFT, ICA, filtering) | ✅ Ready |
| AI Art Generation Engine (GAN + NST) | ✅ Prototype Tested |
| Cognitive State Classifier (SVM + DNN) | ✅ Functional |
| User Interface / Dashboard | 🔄 Under Development |
| VR/AR Integration | 📋 Planned |
| Multi-User Collaborative Mode | 📋 Planned |

> ⏱️ **Estimated time to full working prototype: 6–8 weeks**

---

## 🔮 Future Roadmap

- [ ] 🥽 Full VR/AR integration — navigate 3D brainwave-shaped worlds
- [ ] 👥 Multi-user mode — combine brainwaves for collaborative art
- [ ] 💓 Beyond EEG — add heart rate, skin conductance, respiration sensors
- [ ] 🤖 Personalized AI — model learns and adapts to individual users over time
- [ ] 📱 Mobile app + lightweight wearable EEG device
- [ ] 🏛️ Large-scale public installations with crowd neural activity
- [ ] 🎵 Multisensory — haptic feedback + adaptive soundscapes tied to brainwaves
- [ ] 🏥 Clinical neurofeedback therapy module

---

## 🏢 Potential Industry Partners

| Company | Domain | Website |
|---|---|---|
| Muse | EEG Headsets & Meditation | [choosemuse.com](https://choosemuse.com) |
| Emotiv | EEG Headsets & Cognitive Analytics | [emotiv.com](https://emotiv.com) |
| Neurable | Brain-Computer Interfaces for VR/AR | [neurable.com](https://neurable.com) |
| OpenBCI | Open-source EEG Hardware | [openbci.com](https://openbci.com) |
| MindMaze | Neurotechnology for Healthcare & Gaming | [mindmaze.com](https://mindmaze.com) |
| RunwayML | AI Generative Art & Content Creation | [runwayml.com](https://runwayml.com) |

---

## 🔑 Keywords

`Brainwave-to-Image` • `Brain-Computer Interface (BCI)` • `EEG Signal Processing` • `Neurotechnology` • `AI for Brainwaves` • `EEG-Based Image Generation` • `Cognitive State Visualization` • `Mind-Controlled Art` • `Real-Time EEG Interpretation` • `GAN Art Generation` • `Neural Style Transfer` • `Neurofeedback Art` • `NeuroLoom` • `Deep Learning for EEG` • `Brainwave Creativity Tools`

---

## 📁 Repository Structure

```
📦 NeuroLoom
 ┣ 📁 eeg_acquisition/
 ┃  ┗ 📄 eeg_stream.py           ← OpenBCI / Muse data acquisition
 ┣ 📁 signal_processing/
 ┃  ┣ 📄 preprocessing.py        ← FFT, ICA, artifact removal
 ┃  ┗ 📄 feature_extraction.py   ← Band power, PSD analysis
 ┣ 📁 classification/
 ┃  ┗ 📄 mental_state_classifier.py  ← SVM / DNN cognitive state detection
 ┣ 📁 art_generation/
 ┃  ┣ 📄 gan_model.py            ← GAN art engine
 ┃  ┗ 📄 style_transfer.py       ← Neural Style Transfer (NST)
 ┣ 📁 ui/
 ┃  ┗ 📄 dashboard.py            ← User interface & real-time display
 ┣ 📁 assets/
 ┃  ┗ 🖼️ system-architecture.png ← Architecture diagram
 ┣ 📄 main.py                    ← Entry point — run the full system
 ┣ 📄 requirements.txt           ← Python dependencies
 ┗ 📄 README.md                  ← Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
EEG Hardware: OpenBCI, Muse, or Emotiv headset (or use sample data)
```

### Install Dependencies
```bash
git clone https://github.com/Anandsavran/NeuroLoom.git
cd NeuroLoom
pip install -r requirements.txt
```

### Run with Sample EEG Data (no headset needed)
```bash
python main.py --mode demo
```

### Run with Live EEG Hardware
```bash
python main.py --mode live --device openbci
```

---

## 📖 References

- [OpenBCI Documentation](https://docs.openbci.com/)
- [Muse SDK](https://choosemuse.com/development/)
- [NetworkX + GAN Research — EEG to Image](https://arxiv.org/abs/2205.11094)
- [Neural Style Transfer — Gatys et al.](https://arxiv.org/abs/1508.06576)
- [LSTM-based EEG Contrastive Learning](https://arxiv.org/abs/2104.02687)
- [OpenBCI EEG Community](https://openbci.com/community/)

---

<div align="center">

### 👨‍💻 Lead Inventor & Developer

**Anand Kumar**
B.Tech – Computer Science Engineering (Data Science)
Lovely Professional University, Punjab

*Patent filed under LPU IPR Cell — Invention Disclosure Form submitted for Complete/PCT Filing*

<br/>

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-anandsavarn.vercel.app-00C896?style=for-the-badge)](https://anandsavarn.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Anandsavran-181717?style=for-the-badge&logo=github)](https://github.com/Anandsavran)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/)

<br/>

---

*⭐ Star this repo to follow NeuroLoom's development journey!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4a0080,50:1a0050,100:0d0021&height=100&section=footer" width="100%"/>

</div>
