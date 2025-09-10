# Intelligent Low Carbon Reinforced Concrete Beam Design Optimization via Deep Reinforcement Learning

[![Publication](https://img.shields.io/badge/Scientific%20Reports-Nature-blue?style=flat-square)](https://doi.org/10.1038/s41598-025-18543-4)
[![Demo](https://img.shields.io/badge/Web%20Application-Available-brightgreen?style=flat-square)](https://materialai.ir/RL)

This repository contains the official source code for the paper: **"Intelligent low carbon reinforced concrete beam design optimization via deep reinforcement learning"**, published in *Scientific Reports* (Nature Portfolio).

**Authors:** [Alireza Hosseinzadeh](https://scholar.google.com/citations?user=lIF81MwAAAAJ&hl=en) & [Mehdi Dehestani](https://scholar.google.com/citations?user=pVaNrOcAAAAJ&hl=en)

<div align="center">

---

<a href="https://doi.org/10.1038/s41598-025-18543-4">
  <img src="https://img.shields.io/badge/📄_READ_THE_PAPER-NATURE_SCIENTIFIC_REPORTS-FF0000?style=for-the-badge&logo=nature&logoColor=white&labelColor=CC0000" height="30" alt="Read Paper"/>
</a>



<a href="https://materialai.ir/RL">
  <img src="https://img.shields.io/badge/🚀_TRY_WEB_Application-INTERACTIVE_WEB_APP-00FF00?style=for-the-badge&logo=rocket&logoColor=white&labelColor=00AA00" height="30" alt="Try Demo"/>
</a>

</div>

---

## 📖 Overview

Reinforced concrete (RC) is a primary contributor to the construction industry's carbon footprint. This project introduces an innovative two-stage framework that automates the design of low-carbon RC beams by integrating deep reinforcement learning and artificial neural networks. Our approach tackles the dual challenge of ensuring structural integrity according to engineering codes (ACI 318-19) while actively minimizing embodied carbon emissions.

The framework consists of:

1.  **Stage 1: Predictive Modeling (ANN)**: An Artificial Neural Network (ANN) is trained on a comprehensive dataset to accurately predict concrete's compressive strength and its associated CO₂ emissions based on the mix design. This model achieved an **R² ≈ 0.99** for CO₂ prediction and **R² ≈ 0.85** for compressive strength.
2.  **Stage 2: Design Optimization (Deep RL)**: A Deep Reinforcement Learning (DRL) agent, utilizing Proximal Policy Optimization (PPO), is trained to make sequential design decisions. The agent explores a 13-dimensional action space (geometric and material properties) to find optimal beam designs that minimize CO₂ emissions while satisfying all flexural design criteria of ACI 318-19.

This synergy between predictive analytics and autonomous decision-making provides a powerful, data-driven tool for sustainable structural engineering.

![Framework Overview](Picture1-1.png)
*Figure 1: Two-stage framework architecture for intelligent low-carbon RC beam design*

---
## 🚀 Web Application

We have deployed a web-based tool (https://MaterialAI.ir/RL) that allows users to interact with the trained DRL agent. Users can input beam length, dead load, and live load to receive optimized, low-carbon design alternatives

---
## 🚀 Running on Kaggle

This project can be run entirely on Kaggle, which provides free access to GPUs and a pre-configured environment. This is the recommended approach for training the models.
1. Open the notebook on Kaggle
2. Enable GPU acceleration
3. Run all cells to train your own model

---

## 🎯 Key Features

### 🏗️ **Automated Sustainable Design**
- Generates ACI 318-19 compliant beam designs automatically
- Balances structural integrity with environmental impact
- Handles complex 13-dimensional design parameter space

### 📊 **High-Performance Prediction**
- **R² ≈ 0.99** for CO₂ emission prediction
- **R² ≈ 0.85** for compressive strength prediction
- Reliable foundation for optimization decisions

### 🌱 **Significant Carbon Reduction**
- **43-75% lower CO₂ emissions** compared to baseline methods
- Quantified environmental impact assessment
- Sustainable engineering practices integration

### 🧮 **Advanced AI Architecture**
- **State Space**: 26-dimensional observation space
- **Action Space**: 13-dimensional continuous control
- **Algorithm**: Proximal Policy Optimization (PPO)
- **Constraint Handling**: Non-linear engineering code compliance

---

## 🙏 Acknowledgments

We gratefully acknowledge [Kaggle](https://www.kaggle.com/) for providing free access to GPU resources, which enabled the training and development of the deep reinforcement learning models presented in this work.

---

## 📈 Citing Our Work

If you use this work in your research, please cite our paper:

```bibtex
@article{hosseinzadeh2025intelligent,
  title={Intelligent low carbon reinforced concrete beam design optimization via deep reinforcement learning},
  author={Hosseinzadeh, Alireza and Dehestani, Mehdi},
  journal={Scientific Reports},
  year={2025},
  publisher={Nature Publishing Group},
  doi={10.1038/s41598-025-18543-4}
}
```
---
<div align="center">
  
**⭐ If this project helps your research, please consider giving it a star! ⭐**

</div>
