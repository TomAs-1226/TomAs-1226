# 👋 Hi, I’m TomAs

I’m a student engineer building robotics and AI systems end-to-end — from PCB and embedded firmware to mobile apps, cloud backends, and competition-ready autonomy. This GitHub collects my work across **FRC robotics (2025 “Reefscape”)**, my **Ornimetrics** smart bird-feeder ecosystem, and several supporting tools, libraries, and UIs.

> I value clean architecture, reproducible builds, and thorough documentation. Most projects include setup guides and a short rationale for key design decisions.

---

## 🔭 Current Focus

- **FRC 2025 Robot (“Exodus”)** — WPILib 2025 Java, swerve drive with Pigeon2, PathPlanner autos (L2→Reef→L4 with safe back-off), elevator & climber subsystems, Limelight integration.
- **Ornimetrics** — Raspberry pi hardware + servo dispenser, embedded camera pipeline, YOLOv11 species detection, Flutter mobile app with dashboards and ecological prompts, cloud logging/analytics.
- **SparkHub / Science & Engineering Center** — a student platform (Vue + Rust-WASM engine, Prisma/SQL) for projects, courses, events, and AI-assisted learning tools.

---

## 🚀 Featured Projects

### 1) FRC 2025 “Exodus” Robot Code (Reefscape)
-**Currently featuring experimental code will be made public once preseason comps start** 


### 2) Ornimetrics — Smart Bird-Feeder Ecosystem
- **Hardware:** Raspberry Pi, custom PCB, waterproofed servo drive, camera module, optional Edge-TPU mezz-board.
- **ML:** YOLOv11 species detection; tunable confidence/IOU; exploration of on-device vs. edge acceleration.
- **App:** Flutter (dark/light themes), animated dashboards, species diversity metrics, task prompts.
- **Cloud:** Firebase/Tencent-style logging, analytics, export tools.
- **Repos:**  
  - Model training/inference: https://app.roboflow.com/wksp1/ultimate-ornimetrics-rbnnj/models
  - Flutter app: https://github.com/TomAs-1226/ornimetrics_app

---

## 🧰 Technical Toolbox

**Languages:** Java, Python, TypeScript, Rust, Dart/Flutter, Kotlin  
**Robotics:** WPILib 2025, CTRE Phoenix 6, PathPlanner, Limelight/AprilTags  
**ML/Inference:** Ultralytics YOLOv11, TensorFlow-Lite/ONNX (Edge options), basic data-ops scripts  
**Web/App:** Vue, Vite, Rust-WASM, Prisma/SQL, Flutter  
**Embedded:** ESP32-S3 (IDF/Arduino), servo control, sensor I/O  
**Tooling:** GradleRIO, Git, GitHub Actions, VS Code, Android Studio

---

## 📁 Repository Map 

- **Robotics**
  - `2025-exodus-code` — Reefscape robot (swerve, elevator, climber, autos). 
  - `pathplanner-profiles` — Paths, events, and reusable auto commands. 
- **Ornimetrics**
  - `ornimetrics-firmware` — Rasp-pi firmware & setup code. 
  - `ornimetrics-ai` — YOLOv11 training, export, and inference helpers.
  - `ornimetrics-app` — Flutter app with dashboards & cloud sync. 
- **Platforms & Utilities**
  - `sparkhub` — Student project/course platform (Vue + Rust-WASM + Prisma). 
  - `edge-infer-tools` — ONNX/TFLite conversion, benchmarks, and profiling. 
  - `wpilib-helpers` — Reusable Java utilities for 2025 control loops and telemetry. 


## 📦 Contributing & Branching

- **Flow:** `main` for stable; feature work on `feature/*`.  
- **Commits:** Present tense, concise scope (e.g., `feat: add L2→L4 auto with 4in backoff`).  
- **PRs:** Include a short test plan and screenshots/logs where helpful.  

I welcome issues and thoughtful PRs that include context and measurable outcomes.

---

## 📫 Contact

- GitHub: **@TomAs-1226**  
- email: yu_thomas1226@outlook.com

---
> Last updated: 2025/10/13
