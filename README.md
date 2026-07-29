 # Research Papers & Academic Profile

**Shah Nawaz Ali Asghar**  
B.E. Computer Software Engineering, NUST (graduated May 2026)  
CGPA: 3.13/4.0  
Email: shahnawazaliasghar@gmail.com  
GitHub: [github.com/shahnawaz05](https://github.com/shahnawaz05)  
Phone: +92-349-8193141

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


---

### 2. Browser-Based Gesture Control for Multi-Device Smart Home Appliances Using IoT
**Authors:** Aun Shahid, M. Usman Baig, Shahnawaz Ali Asghar, Umar Hanif  
Military College of Signals, NUST

**Summary**  
We built a fully browser-based pipeline that uses YOLOv11 for appliance detection, MediaPipe Handpose for 21 hand landmarks, and a simple spatial selection rule (wrist-to-bounding-box distance) so the user can point at a device and control it with gestures. Commands are sent to ESP32 relays via Blynk. The system removes the need to open an app or name the device.


---

### 3. MasSecEval – AI-Powered SAST Platform (Final Year Project / Thesis)
**Summary**  
Multi-agent security evaluation platform that combines static analysis with dynamic execution tracing (OpenTelemetry). Uses RAG over a vector store (Qdrant) and an LLM to reason about OWASP Top-10 style vulnerabilities. The system produces ranked findings with evidence from both code and runtime traces.


---
