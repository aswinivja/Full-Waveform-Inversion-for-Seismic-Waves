# Julia Scientific Computing Projects

This repository contains interactive [Pluto.jl](https://github.com/fonsp/Pluto.jl) notebooks demonstrating concepts from computational mathematics and geophysics.

---

## 📂 Contents

### 1. Singular Value Decomposition (SVD)
- Implementation of SVD in Julia
- Applications in:
  - Dimensionality reduction
  - Data compression
  - Matrix approximation
- Visualizations of eigenvalues, singular vectors, and low-rank reconstructions

### 2. Full Waveform Inversion (FWI)
- Pseudo-spectral time-domain simulation of shear-horizontal (SH) seismic waves
- Forward modeling with FFT-based derivatives
- Receiver/source placement and synthetic data generation
- Application of adjoint-state method for Full Waveform Inversion
- Visualization of forward and adjoint fields

---

## 🛠 Technologies
- Julia
- Pluto.jl
- FFTW, LinearAlgebra, SparseArrays
- Plots.jl, StatsPlots.jl

---

## 🚀 Getting Started
Clone the repository and open the Pluto.jl notebooks:
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
julia
using Pluto; Pluto.run()
