# 👋 Hi, I'm Adithya Vardhan Reddy  
**ML Engineer | Computer Vision | Multimodal Retrieval | Architecture-Level R&D**


## 🚀 Overview
ML Engineer specializing in **Computer Vision, Multimodal Retrieval, and Architecture R&D**, focused on building **efficient, interpretable, and reproducible systems under real-world constraints**.

- Design **CPU-efficient pipelines** without relying on heavy GPU scaling  
- Explore **model behavior (failure modes, drift, sensitivity)** beyond surface metrics  
- Build **modular experimental systems** for controlled ablations  
- Work on **architecture-level innovation** (not just training tweaks)  
- Bridge **research ideas → deployable systems**

---

## ⚡ Core Engineering Philosophy
- **Behavior > Benchmark**  
  Accuracy alone is insufficient — emphasis on *why models fail, drift, or destabilize*

- **CPU-first thinking**  
  Systems are designed under constrained compute to expose inefficiencies early

- **Experiments as systems**  
  Reproducibility, parameter isolation, and structured ablations are mandatory

- **Architecture over hacks**  
  Preference for structural improvements vs post-hoc tricks

- **Measure what matters**  
  Latency, FLOPs, stability, ID-switches, and robustness tracked alongside accuracy

---

## 🚀 What I Do
End-to-end engineering across:

### ⚙️ YOLO Architecture Engineering
- Custom modules & backbone–head hybridization (v8 → v11)  
- Cross-generation architecture experiments  
- Shape-consistent YAML integration & profiling  
- CPU-optimized inference workflows

### 🎯 Multi-Object Tracking (MOT)
- Implementations: **SORT / DeepSORT / OCSORT**  
- Custom proxy metrics: ID-switch analysis, track-length stats, active ID curves  
- Trajectory visualizations & tracker behavior comparisons

### 🔍 Multimodal Retrieval Systems
- CLIP-based image–text embeddings  
- NNDescent indexing, UMAP clustering  
- Metadata-conditioned multimodal search

### 🧪 R&D Experimentation
- Reproducible repositories  
- Architecture ablations, profiling, experiment logs  
- CPU-only model debugging pipelines

---

## 🧩 Featured Projects

### 🔵 Vision Systems & Tracking
**VisionTracker**

- End-to-end benchmarking suite combining **YOLOv11 + MOT pipelines**
- Supports **SORT / DeepSORT / OCSORT** with unified evaluation interface
- Tracks **ID-switches, track fragmentation, lifetime statistics**
- Includes **trajectory visualization + sequence-level diagnostics**
- Designed for **real-world comparison**, not just synthetic metrics
  
**Tech:** YOLOv11m, SORT, DeepSORT, OCSORT, custom metrics  
**Repo:** https://github.com/Y-R-A-V-R-5/VisionTracker

---

### 🔵 Architecture Research & YOLO Engineering
**YOLO-Tweaks**
- Cross-generation experimentation (**v8 / v10 / v11 hybrids**)
- Flexible **backbone–head swapping via YAML-driven configs**
- Focus on **tiny-object detection & feature retention**
- Benchmarks **FLOPs vs CPU latency vs accuracy trade-offs**
- Enables rapid testing of **custom modules & structural variants**

**Repo:** https://github.com/Y-R-A-V-R-5/YOLO-Tweaks

---


## 🏗️ Industrial & Private Work (Non-Public Due to IP)

### 🧬 Custom Detection Systems
**SerpensGate-YOLOv8**
- Domain-specific backbone for **plant disease detection**
- Integrates **SerpensELAN, DySnake, CBAM** for feature refinement
- Built as a **CPU-only inference pipeline**
- Optimized for **data-specific patterns rather than generic benchmarks**
- Includes internal evaluation on **robustness to lighting & texture variation**

---

### 🔎 Multimodal Retrieval System
- Built on **CLIP (ViT-B/32) embeddings** for image-text alignment
- Uses **NNDescent for scalable ANN search**
- **UMAP-based clustering** for structure discovery & visualization
- Supports **metadata-conditioned retrieval (filtered semantic search)**
- Designed for **low-latency querying with large embedding spaces**

---

## 🛠 Technical Stack

### ML & Vision
- **PyTorch** for flexible model experimentation and low-level control  
- **YOLO (v8–v11)** with custom architectural modifications  
- **OpenCV** for preprocessing, pipeline integration, and visualization  
- Strong focus on **CPU-bound optimization and profiling**

### Retrieval & Indexing
- **CLIP** for multimodal embedding generation  
- **FAISS / NNDescent** for efficient nearest neighbor search  
- Emphasis on **scalable indexing under memory constraints**

### Engineering & Systems
- **Python** with modular, reusable pipeline design  
- **Git** for version-controlled experimentation  
- Structured workflows for **ablation tracking and reproducibility**

### Visualization & Analysis
- **Matplotlib / Seaborn** for deep experiment inspection  
- Custom plots for **tracking metrics, drift, and scaling behavior**

---

## 🎯 Current Research Directions
- **Long-context vision architectures**  
  Exploring how spatial dependencies scale beyond standard receptive fields  

- **Efficient MOT without heavy re-ID**  
  Reducing dependency on appearance embeddings while maintaining ID stability  

- **Multimodal fusion systems**  
  Aligning image-text representations beyond basic embedding similarity  

- **CPU-first model optimization**  
  Identifying architectural bottlenecks under constrained compute  

- **Model behavior diagnostics**  
  Studying sensitivity to noise, resolution shifts, and distribution drift  

---

## 📈 Experimental Mindset & Research Approach
- Treat every project as a **controlled experiment**, not a one-off implementation  
- Design **ablation-first workflows** to isolate architectural impact  
- Track **non-obvious metrics** (stability, variance, failure patterns)  
- Emphasize **repeatability across seeds, configs, and environments**  
- Prefer **small, explainable experiments** over large opaque training runs  

---

## 🌐 Connect & Work
- Open to **research collaborations and system-level ML discussions**  
- Interested in **architecture R&D, efficient vision systems, and retrieval pipelines**  
- Focused on roles involving **deep experimentation, not just model usage**  
- GitHub: https://github.com/Y-R-A-V-R-5  
- LinkedIn: https://www.linkedin.com/in/yravr/  
- Email: adithyavardhanreddy2003@gmail.com  

---

Thanks for stopping by — feel free to explore my work and reach out! 🚀
