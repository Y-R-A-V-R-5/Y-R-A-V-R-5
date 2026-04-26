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

### 🔵 **1. VisionTracker — YOLOv11 + Multi-Object Tracking Benchmarking**

- End-to-end benchmarking suite combining **YOLOv11 + MOT pipelines**
- Supports **SORT / DeepSORT / OCSORT** with unified evaluation interface
- Tracks **ID-switches, track fragmentation, lifetime statistics**
- Includes **trajectory visualization + sequence-level diagnostics**
- Designed for **real-world comparison**, not just synthetic metrics
  
**Tech:** YOLOv11m, SORT, DeepSORT, OCSORT, custom metrics  
**Repo:** https://github.com/Y-R-A-V-R-5/VisionTracker

---

### 🔵 **2. YOLO-Tweaks — Cross-Generation YOLO Hybrid Architectures**
Treating YOLO as a modular architecture rather than a fixed model.

**Includes:**
- Backbone–head swapping (v8, v10, v11)  
- Custom hybrids (v8v10, v10v11, v11v8)  
- Tiny-object specialization on AgriPest  
- FLOPs/params vs CPU latency profiling  
- Tensor-shape validation tooling

**Repo:** https://github.com/Y-R-A-V-R-5/YOLO-Tweaks

---

### 🔵 **3. SerpensGate-YOLOv8 (Company Project — Summary Only)**
Custom plant-disease detection backbone with:
- SerpensELAN, C2f-DySnake, SerpensCBAM  
- Modified SPPF + full Ultralytics registry integration  
- CPU-only training pipelines  
*(Internal repo; code not public)*

---

### 🔵 **4. CLIP-Based Zero/Few-Shot Retrieval System (Company Project — Summary Only)**
Deployed multimodal retrieval PoC using:
- CLIP ViT-B/32 embeddings  
- NNDescent + UMAP indexing  
- Metadata-conditioned text guidance  
*(Internal repo; code not public)*

---

## 🛠 Tech Stack

**ML & Vision:**  
PyTorch, Ultralytics YOLO (v8–v11), OpenCV  

**Retrieval & Embeddings:**  
CLIP, FAISS, NNDescent  

**Engineering:**  
Python, Git, Reproducible ML repos, modular YAML/registry design  

**Visualization:**  
Matplotlib, Seaborn  

**Special Focus:**  
CPU-optimized inference  
Architecture ablations  
Custom module integration  

---

## 🎯 What I'm Exploring
- Long-context vision architectures  
- Efficient MOT without re-ID models  
- Multimodal fusion for retrieval  
- Model compression & CPU-first detectors  

---

## 🌐 Connect With Me
- **LinkedIn:** https://www.linkedin.com/in/yravr/  
- **Email:** adithyavardhanreddy2003@gmail.com  

---

Thanks for stopping by — feel free to explore my work and reach out! 🚀
