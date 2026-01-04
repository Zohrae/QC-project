# Quantum States Project: 3-Qubit GHZ and W States

## Overview

This project explores **three-qubit entangled states** using **Qiskit**.  
We construct **GHZ** and **W states**, simulate measurements, analyze **density matrices**, and study **entanglement** and **robustness**.

---

## Tools & Libraries

We used the following tools:

- ![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python&logoColor=white)  
- ![Qiskit](https://img.shields.io/badge/Qiskit-0.53.1-purple?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![NumPy](https://img.shields.io/badge/NumPy-1.26-orange?style=for-the-badge&logo=numpy&logoColor=white)  
- ![Pandas](https://img.shields.io/badge/Pandas-2.1-lightblue?style=for-the-badge&logo=pandas&logoColor=white)  
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-green?style=for-the-badge&logo=matplotlib&logoColor=white)  
- ![SciPy](https://img.shields.io/badge/SciPy-1.11-red?style=for-the-badge&logo=scipy&logoColor=white)  
- ![Qiskit QuantumCircuit](https://img.shields.io/badge/QuantumCircuit-Qiskit-blueviolet?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit AerSimulator](https://img.shields.io/badge/AerSimulator-Qiskit-darkblue?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit Statevector](https://img.shields.io/badge/Statevector-Qiskit-blue?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit DensityMatrix](https://img.shields.io/badge/DensityMatrix-Qiskit-purple?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit partial_trace](https://img.shields.io/badge/partial_trace-Qiskit-darkpurple?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit entropy](https://img.shields.io/badge/entropy-Qiskit-pink?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit transpile](https://img.shields.io/badge/transpile-Qiskit-blueviolet?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit execute/run](https://img.shields.io/badge/execute/run-Qiskit-darkblue?style=for-the-badge&logo=qiskit&logoColor=white)  
- ![Qiskit plot_histogram](https://img.shields.io/badge/plot_histogram-Qiskit-green?style=for-the-badge&logo=qiskit&logoColor=white)  


---

## Features

- **GHZ Circuit**: Hadamard + CNOT gates → |000⟩ + |111⟩  
- **W Circuit**: Controlled rotations + Toffoli → |001⟩ + |010⟩ + |100⟩  
- **Simulations**: QASM and statevector simulators  
- **Analysis**: Probabilities, chi-squared test, density matrices  
- **Entanglement**: Von Neumann entropy, purity, partial traces  
- **Robustness**: Effects of tracing out a qubit  
- **Visualizations**: Circuit diagrams, 2D & 3D histograms, heatmaps  


