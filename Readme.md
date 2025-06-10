# Balancing Beyond Discrete Categories: Continuous Demographic Labels for Fair Face Recognition

📄 **Paper:** [arXiv:2506.01532](https://arxiv.org/abs/2506.01532)  
🧑‍🔬 **Authors:** Pedro C. Neto, Naser Damer, Jaime S. Cardoso, Ana F. Sequeira
📅 **Published:** 2025  
📦 **Data:** [Hugging Face Dataset Collection](https://huggingface.co/collections/netopedro/continuous-ethnicity-face-recognition-683d775e507954149965e5b6)

---

## 🔍 Overview

Face recognition systems often simplify demographic identity into **discrete categories** like _Asian_, _Black_, or _White_. However, such simplifications:

- Ignore the **complexity of human ethnicity**
- Introduce **dataset imbalance artifacts**
- Lead to **biased model performance**

In this work, we propose a new approach:

✅ **Model ethnicity as a continuous variable** rather than a one-hot class  
✅ **Balance datasets using label distributions** instead of equal group sizes  
✅ **Evaluate models** across finely-grained demographic axes  
✅ **Demonstrate that fairness and accuracy can coexist**

---

## 🧠 Key Findings

- **Continuous demographic labels** (e.g., 3D ethnicity embeddings) lead to **better subgroup fairness** than discrete group labels.
- We introduce **distribution-aware dataset balancing** techniques (e.g., histogram binning + sampling) that preserve diversity and fairness.
- Trained and evaluated **65+ face recognition models** across **20+ dataset variants**.
- **Fairness improved** (lower standard deviation in subgroup performance) **without sacrificing accuracy**.
- The approach is generalizable to other domains (e.g., voice, gait, healthcare).

---

## 📦 Datasets
All datasets (including continuous demographic annotations) are hosted on Hugging Face:

📂 Hugging Face Collection → [Hugging Face Dataset Collection](https://huggingface.co/collections/netopedro/continuous-ethnicity-face-recognition-683d775e507954149965e5b6)

## 🚀 Training

To be added

## 🤝 Citation

### If you use this work, please cite:

@article{neto2025balancing,
  title={Balancing Beyond Discrete Categories: Continuous Demographic Labels for Fair Face Recognition},
  author={Neto, Pedro C and Damer, Naser and Cardoso, Jaime S and Sequeira, Ana F},
  journal={arXiv preprint arXiv:2506.01532},
  year={2025}
}
