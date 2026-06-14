<div align="center">
<h1>GeoTeacher</h1>
<h3>GeoTeacher:Geometry-Guided Semi-Supervised 3D Object Detection /h3>

[Jingyu Li](https://sii-whaleice.github.io/)<sup>1,2\*</sup>, Xiaolong Zhao<sup>3\*</sup>, Zhe Liu<sup>4</sup>, Wenxiao Wu<sup>5,2</sup>, [Li Zhang](https://lzrobots.github.io/)<sup>1,2✉</sup>  

<sup>1</sup>Fudan University  <sup>2</sup>Shanghai Innovation Institute
<sup>3</sup> Tongji University <sup>4</sup> Hong Kong University <sup>5</sup> Huazhong University of Science and Technology

(\*) Equal contribution. (✉) Corresponding author.  

ICRA 2026

<a href="[https://arxiv.org/abs/2512.23147](https://arxiv.org/abs/2512.23147)"><img src='https://img.shields.io/badge/arXiv-GeoTeacher-red' alt='Paper PDF'></a>
</div>

🔥 Official implementation of **GeoTeacher**


## Notice

This repository is no longer actively maintained, as our research focus has shifted away from semi-supervised 3D object detection.
If you are interested in this project or require access to related code, please feel free to contact the authors via email.


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


## 🚀 Installation

```bash
git clone https://github.com/USERNAME/GeoTeacher.git
cd GeoTeacher

conda create -n geoteacher python=3.10
conda activate geoteacher

pip install -r requirements.txt
