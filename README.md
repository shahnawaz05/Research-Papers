# Research Papers & Academic Profile

**Shah Nawaz Ali Asghar**  
B.E. Computer Software Engineering, NUST (graduated May 2026)  
CGPA: 3.13/4.0  
Email: shahnawazaliasghar@gmail.com  
GitHub: [github.com/shahnawaz05](https://github.com/shahnawaz05)  
Phone: +92-349-8193141

This repository collects my main research papers, project reports, and a clean academic CV prepared for graduate applications (KAIST Spring 2027 and similar programs).

---

## Papers

### 1. Curriculum Constraint Tightening in Lagrangian PPO
**Full title:** Curriculum Constraint Tightening in Lagrangian PPO: A Controlled Empirical Study of λ Stability and Generalization in Discrete Navigation

**Summary**  
I studied how curriculum schedules for the constraint budget affect the dual variable (λ) in Lagrangian PPO. Experiments on a discrete navigation gridworld with held-out maps showed that progressive tightening produces a more stable λ trajectory, but the multiplier settles at a lower equilibrium. This weaker safety signal leads to noticeably worse zero-shot generalization compared with a fixed-target baseline. The paper isolates the arithmetic mechanism behind the trade-off.

**Key numbers**  
- Curriculum λ stayed in 0.38–0.42 range  
- Standard Lagrangian climbed to ~0.67  
- Zero-shot success on unseen maps: Standard 75.3% vs Curriculum 56.3%

**Code & results:** [github.com/shahnawaz05/Safe_cirriculum](https://github.com/shahnawaz05/Safe_cirriculum)  
**PDF:** (upload the clean PDF of the paper into this repo)

---

### 2. Browser-Based Gesture Control for Multi-Device Smart Home Appliances Using IoT
**Authors:** Aun Shahid, M. Usman Baig, Shahnawaz Ali Asghar, Umar Hanif  
Military College of Signals, NUST

**Summary**  
We built a fully browser-based pipeline that uses YOLOv11 for appliance detection, MediaPipe Handpose for 21 hand landmarks, and a simple spatial selection rule (wrist-to-bounding-box distance) so the user can point at a device and control it with gestures. Commands are sent to ESP32 relays via Blynk. The system removes the need to open an app or name the device.

**PDF:** (upload SmartHome paper PDF into this repo)

---

### 3. MasSecEval – AI-Powered SAST Platform (Final Year Project / Thesis)
**Summary**  
Multi-agent security evaluation platform that combines static analysis with dynamic execution tracing (OpenTelemetry). Uses RAG over a vector store (Qdrant) and an LLM to reason about OWASP Top-10 style vulnerabilities. The system produces ranked findings with evidence from both code and runtime traces.

**Note:** Full thesis is large. A short abstract or selected chapters can be added here if needed. Keep the complete thesis private unless required.

---

## Academic CV (for KAIST and similar applications)

**Shah Nawaz Ali Asghar**  
Islamabad, Pakistan  
+92-349-8193141 | shahnawazaliasghar@gmail.com  
GitHub: github.com/shahnawaz05

### Education
**National University of Sciences and Technology (NUST), Islamabad**  
B.E. in Computer Software Engineering  
CGPA: 3.13 / 4.0  
Oct 2022 – May 2026 (graduated)

### Research Interests
Safe and constrained reinforcement learning, Lagrangian methods for CMDPs, multi-agent systems, computer vision for physical control, trustworthy AI.

### Publications / Research
- **Curriculum Constraint Tightening in Lagrangian PPO: A Controlled Empirical Study of λ Stability and Generalization in Discrete Navigation** (preprint). Empirical analysis of dual-variable dynamics under curriculum constraint schedules and the resulting generalization trade-off. Code: github.com/shahnawaz05/Safe_cirriculum
- **Browser-Based Gesture Control for Multi-Device Smart Home Appliances Using IoT** (co-authored technical paper). YOLOv11 + Handpose + ESP32 pipeline for camera-based appliance control.

### Research Experience & Selected Projects
**Curriculum Constraint Tightening in Lagrangian PPO**  
Designed and ran controlled experiments comparing unconstrained, standard Lagrangian, curriculum, and fixed-λ ablation conditions on a discrete navigation task. Identified and explained the mechanism by which curriculum schedules can stabilize λ while weakening the final safety signal.

**MasSecEval – AI-Powered SAST Platform (Final Year Project)**  
Built a multi-agent system that combines static analysis, OpenTelemetry execution tracing, and RAG for security vulnerability evaluation aligned with OWASP Top-10 categories.

**Smart Home Gesture Control System**  
Co-developed a browser-based IoT control system using object detection and hand landmarks for spatial selection and physical actuation via ESP32.

### Professional Experience
**AI Connect Hub (Managed by Growlatics)** – Remote  
Artificial Intelligence Engineer  
Aug 2025 – Present  
- Designed and deployed multiple production multi-agent systems (LangGraph / LangChain) for voice, marketing, health, meeting, and administrative workflows.  
- Worked on latency, reliability, and scaling of cloud-native AI services on Azure.

**Incept AI**  
Backend + AI Intern  
Oct 2023 – Feb 2024  
- Built prompt-chaining pipelines and sandbox testing workflows for a prompt-to-code SaaS product.

### Technical Skills
- **Reinforcement Learning & ML:** Lagrangian PPO, DQN variants, constrained MDPs, PyTorch  
- **Multi-Agent & LLMs:** LangGraph, LangChain, RAG (FAISS / Qdrant), prompt engineering  
- **Computer Vision & IoT:** YOLOv11, MediaPipe / Handpose, ESP32, edge actuation  
- **Languages & Tools:** Python, C++, JavaScript/TypeScript, FastAPI, Docker, Azure

### Additional Information
- Medium of Instruction for the degree was English.  
- Available for Spring 2027 intake.

---

## How to use this repository

1. Upload the clean PDF of the Lagrangian PPO paper and name it clearly.  
2. Upload the IoT paper PDF if you want it public.  
3. Keep the full MasSecEval thesis private unless a professor specifically requests it.  
4. Link this repository (or the individual Safe_cirriculum repo) in your cold emails and application materials.

Questions or updates: shahnawazaliasghar@gmail.com
