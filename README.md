
# 🧠 Deep Learning Homework - Conda Environment Setup

---

This repository provides instructions to set up a conda environment to run  deep learning homework in Jupyter Notebook. All outputs are pre-generated, but you can re-run any cell as needed.

---

## 🚀 1. Create a new conda environment

Open Anaconda Prompt or your terminal and run:

```bash
conda create -n dl_hw1 python=3.9
```

## ▶️ 2. Activate the environment

```bash
conda activate dl_hw1
```

## 📦 3. Install required packages

**For CPU only:**
```bash
conda install jupyter numpy matplotlib
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

**For GPU (if supported):**
```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```

## 📓 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `Hw1-1.ipynb` in your browser.

- **No need to download training data:** It already exists in the repo.
- **All outputs are pre-generated:** You can re-run any cell if you wish.
- **Some cells may take significant time to run.**

---

## 📑 Sections inside notebook (as per report)

- **HW1-1 Deep vs Shallow**
- **Simulate a Function**
- **1-1 Part B**
- **Train on actual task**
- **Model Definitions (ShallowCNN, DeepCNN)**
- **Parameter Matching and Model Configurations**
- **Training and Evaluation**
- **Visualization of Training and Results**
- **HW 1-2 Optimization**
- **Visualize the optimization process**
**Observing Gradient Norm and Loss During Training**
**:warning: What Happens When Gradient is Almost Zero (Takes a long time to run)**
**HW 1-3: Can Network Fit Random Labels**
**Number of Parameters vs Generalization**
**:warning: Interpolate Between Two Trained CNNs (Different Training: Batch Size & LR) (Takes a long time to run)**
**:warning: Flatness vs. Generalization — Part 2 (MNIST) (Takes a long time to run)**






=======
# CPSC-8430-Deep-Learning_homework1
>>>>>>> 1c105e533b7dbf2d52fe06ce96214305d3e7d992
