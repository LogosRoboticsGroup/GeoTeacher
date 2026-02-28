# GeoTeacher
> Geometry-Guided Semi-Supervised 3D Object Detection  
> [ICRA 2026]

🔥 Official implementation of **GeoTeacher**

---

## 📢 News
- **Feb. 28, 2026 🎉** GeoTeacher has been accepted to ICRA 2026!
- **TODO:** Code release
- **TODO:** Pretrained models
- **TODO:** Demo video

---

## 🧠 Overview
GeoTeacher is a geometry-guided semi-supervised framework for 3D object detection.  
It leverages geometric consistency between teacher and student models to improve detection performance with limited annotations.

**Key ideas:**
- Geometry-guided consistency learning
- Semi-supervised training pipeline
- Robust teacher-student framework

---

## 🏗️ Method
<p align="center">
  <img src="assets/pipeline.png" width="80%">
</p>


### Qualitative Results

<p align="center">
  <img src="assets/results.png" width="80%">
</p>

---

## 🚀 Installation

```bash
git clone https://github.com/USERNAME/GeoTeacher.git
cd GeoTeacher

conda create -n geoteacher python=3.10
conda activate geoteacher

pip install -r requirements.txt
