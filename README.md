# Full Waveform Inversion (FWI) – SH Waves (Julia + Pluto.jl)

This repository contains an **interactive Pluto.jl notebook** for **Full Waveform Inversion (FWI)** of 2-D seismic SH waves.  
The implementation focuses on pseudo-spectral methods for solving the seismic wave equation and gradient-based inversion.

---

##  Features
- FFT-based **pseudo-spectral differentiation** for fast and accurate spatial derivatives.
- Explicit **time-stepping scheme** for stress–velocity updates.
- Simulation of **synthetic seismic data** with density perturbations.
- Implementation of **adjoint-state method** for gradient calculation (∇ρ and ∇μ).
- Interactive visualization of:
  - Wave propagation
  - Observed vs. modeled data
  - Misfit reduction
  - Gradient fields

---

##  Tech Stack
- **Language**: Julia (v1.8+)
- **Notebook**: Pluto.jl
- **Libraries**: FFTW, LinearAlgebra, Plots, PlutoUI, SparseArrays

---

## 📊 Applications
- Seismic imaging & geophysical inverse problems  
- Earth structure studies (density/velocity perturbations)  
- Educational demonstrations of **computational seismology**


##  How to Run
1. Install [Julia](https://julialang.org/) (v1.8+ recommended)
2. Add Pluto.jl:  
   ```julia
   using Pkg
   Pkg.add("Pluto")
