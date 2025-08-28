# Analytical Model of Trap Limited Transport in Single-Carrier Devices

This project contains a Jupyter Notebook that models **trap-limited transport (TLT)** in single-carrier devices under different voltage regimes. The notebook implements analytical equations describing the current density (J) as a function of applied voltage (V), device length (L), and material parameters.

---

## 📖 Model Overview

The notebook evaluates three transport regimes:

- **Low Voltage**  
  J₁ = α V

- **Intermediate Voltage**  
  J₂ = β V^(l+1)

- **High Voltage (Mott-Gurney Law)**  
  J₃ = γ V²

Where parameters depend on carrier mobility (μ), trap density (Nₜ), dielectric constant (εᵣ), and other physical constants.

---

## 🛠 Requirements

The notebook uses standard scientific Python libraries:

```bash
numpy
matplotlib
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/emmettralston/CarbonFootprintPoC.git
   cd CarbonFootprintPoC
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open **`Analytical_Model_TLT_Single_Carrier.ipynb`** to explore the equations and plots.

---

## 📊 Outputs

- Analytical expressions for current density across regimes.
- 2D and 3D plots of J vs. V.
- Visual demonstrations of scaling behavior in trap-limited transport.

---

## 📌 Notes

This notebook is intended for research and educational use. It provides a compact framework for analyzing trap-limited current conduction and comparing analytical predictions with experimental or numerical data.
