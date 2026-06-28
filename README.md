# 🎰 Slot Machine Analysis – Low Volatility Model

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

## 📋 Overview

Comprehensive mathematical and statistical analysis of a low-volatility slot machine with **3 reels**, **30 symbols**, and **8 paylines**.

**Key Specs:**
- 3 reels × 30 symbols = 27,000 combinations
- 5 special symbols (1-5) return the bet when in middle position
- Paytable: 2 matches → 6×, 3 matches → 200×
- 8 paylines across a 3×3 grid

**Methodologies:** Monte Carlo Simulation, RTP Analysis, VaR, Bayesian Inference

---

## 📊 Key Results

| Metric | Result | Status |
|--------|--------|--------|
| **RTP** | 95.188% | ✅ Target 95% |
| **Volatility (CV)** | 2.61 | ✅ Low |
| **Hit Rate** | 72.92% | ✅ High engagement |
| **3-Match (per line)** | 0.1109% (1 in 902) | ✅ Matches theory (1 in 900) |
| **3-Match (per spin)** | 0.8872% (1 in 113) | ✅ Matches theory (1 in 112.5) |
| **VaR (95%)** | 0 credits | ✅ Low risk |

**72/28 weight distribution** – Low-Risk (2,610 × 6 = 15,660) / High-Risk (30 × 200 = 6,000)

---

## 🛠️ Tech Stack

`Python` · `NumPy` · `SciPy` · `Matplotlib` · `Jupyter`

## 📁 Files

- `casino_slot_simulation_low_volatility.ipynb` – Main analysis notebook
- `requirements.txt` – Dependencies

## 🚀 Run It

```bash
pip install numpy scipy matplotlib jupyter
jupyter notebook casino_slot_simulation_low_volatility.ipynb
