## Hassan Behbahani Pour

Data and machine learning. Based in London.

MSc Data Science and Artificial Intelligence (Merit) — Bournemouth University
BSc Computer Engineering — American University of the Middle East

---

### What I've been working on

**[Explainable Deep Learning for Predicting Alzheimer's Progression from Mild Cognitive Impairment](https://github.com/Hassan-mb/explainable-ad-progression)** — my MSc dissertation.

A multimodal model predicting MCI-to-Alzheimer's conversion from structural MRI and clinical
data: a 3D ResNet-18 fused with a clinical MLP, trained on 969 ADNI subjects. It reaches
**0.838 AUC** on a held-out test set.

The accuracy isn't the interesting part. I tested whether the model's own explanations were
stable, and they weren't. Grad-CAM attributions varied substantially across independent
training runs — mean Spearman ρ of **0.123** — while SHAP rankings held at **0.871**. Same
architecture, same data, a different random seed, a different explanation.

Nothing in the accuracy numbers tells you that. A model can be right and still be explained
wrongly, which matters a great deal when the explanation is what persuades a clinician to act.

---

### What I work with

**Data & ML** — Python, PyTorch, pandas, NumPy, scikit-learn, SHAP, Grad-CAM, nibabel, ANTsPy
**Web** — JavaScript, React, React Native, Node.js, Express, MongoDB
**Hardware** — embedded systems, microcontrollers, circuit design, Verilog, C

---

### Before the MSc

I trained as a computer engineer and completed the CODED full-stack bootcamp. My graduation
project — a driver monitoring system detecting drowsiness and distraction from facial
recognition and sensor data — won **Best Graduation Project 2024** at AUM.

---

Open to data analyst, data science and machine learning roles in London.

[LinkedIn](https://www.linkedin.com/in/hassan-behbahani-pour)
