  
### *Bell Inequality Violation on IBM Quantum Processors: Noise Impact on Distant Qubit Entanglement*

**Author:** Luan Almeida Meira, Pedro Silva Correia  
**Institution:** Universidade Estadual de Santa Cruz (UESC), Brazil  
**Department:** DCEX - NEmes  

---

## 🧭 Overview  
This repository explores **Bell inequality violation** and **quantum state tomography** using **IBM Quantum Processors** and open-source frameworks such as **Qiskit** and **QuTiP**.  
The main goal is to investigate how **noise** affects **entanglement** between **distant qubits**, both theoretically and through simulations on real quantum hardware.

---

## ⚛️ Theoretical Background  

- **Bell’s Inequality:**  
  Introduced by *John S. Bell* in 1964, the inequality tests the fundamental differences between quantum mechanics and classical local hidden-variable theories.  
  A violation of the inequality (S > 2) demonstrates **non-local correlations** — a hallmark of quantum mechanics.

- **Entanglement over distance:**  
  Entangled qubits may be physically separated yet remain correlated. This work analyses how spatial separation and device-level noise influence the **strength and purity** of entanglement.

- **Noise modelling:**  
  Includes amplitude damping, phase damping, depolarising and readout noise channels — all implemented via IBM’s noise models and validated using QuTiP simulations.

- **Quantum state tomography:**  
  The reconstruction of the two-qubit **density matrix (ρ)** through measurement statistics, enabling quantitative evaluation of:
  - Concurrence  
  - Fidelity  
  - Trace distance 
  - Bell-violation metrics (S-value)

---

## 🧩 Project Structure  
.
├── notebooks/
│ ├── Bell's Inequally.ipynb # Bell inequality violation on IBM processors
│ └── Tomography Singlet.ipynb # Quantum state tomography of the singlet state
├── requirements.txt # Dependencies (Qiskit, QuTiP, NumPy, etc.)
└── README.md
```bash
git clone https://github.com/phys-luan/Bell-Violation-on-IBM-QP-Noise-Impact-on-Distant-Qubit-Entanglement.git
cd Bell-Violation-on-IBM-QP-Noise-Impact-on-Distant-Qubit-Entanglement
