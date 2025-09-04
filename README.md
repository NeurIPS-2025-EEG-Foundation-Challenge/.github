# 🧠 NeurIPS 2025 EEG Foundation Challenge

<p align="center">
  <img src="https://eeg2025.github.io/assets/img/workflow.png" style="max-width: 600%;" alt="EEG Challenge Logo"/>
</p>

<p align="center">
  <a href="https://github.com/eeg2025"><img alt="Official GitHub" src="https://img.shields.io/badge/Official_Challenge_Org-eeg2025-blue?logo=github"></a>
  <a href="https://arxiv.org/abs/2506.19141"><img alt="Paper" src="https://img.shields.io/badge/arXiv-2506.19141-b31b1b?logo=arxiv"></a>
  <a href="https://neurips.cc/Conferences/2025/CompetitionTrack"><img alt="NeurIPS 2025" src="https://img.shields.io/badge/Competition-NeurIPS_2025-orange"></a>
</p>

This GitHub organization hosts the collective efforts, code, and resources for our team's participation in the **2025 EEG Foundation Challenge: From Cross-Task to Cross-Subject EEG Decoding**, accepted to the NeurIPS 2025 Competition Track.

---

## 🎯 The Challenges

Our objective is to develop state-of-the-art models to tackle two distinct but related challenges in EEG decoding.

| Challenge                               | Final Score Weight | Goal                                                                        | Evaluation Metric          |
| --------------------------------------- | :----------------: | --------------------------------------------------------------------------- | -------------------------- |
| **1. Cross-Task Transfer Learning** |        `30%`         | Predict `response times` by transferring knowledge from passive to active tasks. | Normalized RMSE (`NRMSE`) |
| **2. Psychopathology Factor Prediction**|        `70%`         | Predict clinical `psychopathology factors` using subject-invariant representations. | Normalized RMSE (`NRMSE`) |

---

## 💻 Our Repositories

This organization contains all codebases related to our project. Each repository serves a specific purpose as outlined below.

| Repository                                     | Description                                                                                             |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **[Challenge1](https://github.com/NeurIPS-2025-EEG-Foundation-Challenge/Challenge1)** | A dedicated repository for developing and testing models specifically for `Challenge 1`. |
| **[Challenge2](https://github.com/NeurIPS-2025-EEG-Foundation-Challenge/Challenge2)** | A dedicated repository for developing and testing models specifically for `Challenge 2`. |
| **[startkit](https://github.com/NeurIPS-2025-EEG-Foundation-Challenge/startkit)** | A Jupyter Notebook version of the official starter kit, adapted and shared by `JM` for rapid prototyping and analysis. |
| **[Unified-NeurIPS-2025-EEG-Challenge](https://github.com/NeurIPS-2025-EEG-Foundation-Challenge/Unified-NeurIPS-2025-EEG-Challenge)** | The primary, unified repository integrating all final code, experiments, and submission logic for both challenges. |

---

## 🧠 Dataset Overview

* **Primary Data:** We are using the **Healthy Brain Network (HBN) EEG Dataset**, which includes recordings from over 3,000 participants across six distinct cognitive tasks.
* **Key Constraint:** As per the competition rules, all development and evaluation must be performed on the **100Hz downsampled** dataset. The official format is `BDF`.
* **Target Variables:**
    1.  **Response Time** for each trial in active tasks.
    2.  Four **Psychopathology Dimensions** (`p-factor`, `internalizing`, `externalizing`, `attention`).

## ✅ Competition Rules & Submission

A brief summary of the key rules:
- All evaluation will be performed on the **100Hz downsampled data**.
- Use of external datasets and pre-trained models is allowed but must be documented.
- This is a **code submission** competition.
- Final models must be runnable on a **single GPU with 20GB of VRAM** at the inference stage.

## 📚 Key Resources

For all team members, please familiarize yourself with the official materials.

* **Official Challenge Website:** [NeurIPS 2025 Competition Track](https://neurips.cc/Conferences/2025/CompetitionTrack)
* **Official GitHub Organization:** [github.com/eeg2025](https://github.com/eeg2025)
* **Official Start Kit Repo:** [github.com/eeg2025/startkit](https://github.com/eeg2025/startkit)
* **Primary Research Paper:** [*HBN-EEG: The FAIR implementation...* (arXiv:2506.19141)](https://arxiv.org/abs/2506.19141)

