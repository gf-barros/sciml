# 🤖 Scientific Machine Learning (SciML)

Welcome to my study repository on **Scientific Machine Learning (SciML)** — where physics meets machine learning!  
This repository explores hybrid approaches that blend data-driven models with physical knowledge to solve complex scientific problems.

Here, you'll find implementations, notes, and experiments in both **Python** and **C++**, covering key SciML methods with a focus on clarity and reproducibility.

---

## 📚 Topics Covered

This repository is organized into core themes within Scientific ML:

### 📐 Physics-Informed Neural Networks (PINNs)
- Solving PDEs with neural networks
- Loss functions that incorporate physics constraints
- Applications to forward and inverse problems

### 🧩 Reduced Order Models (ROMs)
- Proper Orthogonal Decomposition (POD)
- Autoencoder-based ROMs
- Galerkin projection methods

### 🌊 Dynamic Mode Decomposition (DMD)
- Standard and extended DMD
- Koopman operator theory
- Applications to fluid flow and time-series analysis

### 🔄 Operator Learning
- DeepONet, Fourier Neural Operators (FNOs)
- Learning mappings between function spaces

### 📊 Data-Driven Discovery of Equations
- Sparse Identification of Nonlinear Dynamics (SINDy)
- Symbolic regression for physics discovery

---

## 🚀 Repository Structure

```
scientific-ml/
├── pinns/
│   ├── python/
│   └── cpp/
├── roms/
├── dmd/
├── operator_learning/
├── equation_discovery/
└── README.md
```

Each method folder includes:
- `python/` — Clean code using PyTorch, NumPy, etc.
- `cpp/` — Efficient implementations for high-performance scenarios
- `README.md` — Explanations, references, and run instructions

---

## 🛠️ Getting Started

### Requirements (for Python)
- Python 3.8+
- NumPy
- SciPy
- PyTorch or TensorFlow (depending on the example)
- Matplotlib / Plotly

Install all dependencies using:

```bash
pip install -r requirements.txt
```

### C++ Examples
Some methods may include C++ implementations using Eigen or other scientific libraries. Most use **CMake** for portability:

```bash
mkdir build && cd build
cmake ..
make
./your_executable
```

---

## ✨ Why This Exists

Scientific Machine Learning is redefining how we model the world. By merging physics-based models and machine learning, we can create interpretable, efficient, and accurate systems. This repository is my way of deeply understanding the field by implementing its core ideas.

<!-- ---

## 📘 References & Suggested Reading

- **Physics-Informed Machine Learning** – Karniadakis et al.
- **Machine Learning for Physics and the Physics of Learning** – Mehta et al.
- **Data-Driven Science & Engineering** – Brunton & Kutz
- **Neural Operator Learning** – Kovachki et al. -->

---

## 🤝 Contributions

This is primarily a learning repository, but contributions, questions, and suggestions are always welcome.

---

## 📬 Contact

Let's connect on [LinkedIn](https://www.linkedin.com/in/gabrielfbarros/) or feel free to open an issue. I'm always open to discussing scientific ML and collaborations.
