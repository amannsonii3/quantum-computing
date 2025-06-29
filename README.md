# Quantum Computing with Qiskit

This repository contains Jupyter notebooks exploring quantum computing concepts using IBM's Qiskit framework.

## Notebooks

### 1. `ep2_Installation.ipynb`
- Qiskit installation and setup
- Environment configuration
- Basic imports and verification

### 2. `ep3_Not_So_HelloWorld.ipynb`  
- Bell state creation and analysis
- Pauli operator expectation values
- 100-qubit GHZ state experiment
- Quantum decoherence demonstration
- Error mitigation techniques (M3, Dynamical Decoupling)
- Real quantum hardware execution

## Key Concepts Covered

- **Quantum Circuits**: Creating and manipulating quantum circuits
- **Bell States**: Entangled two-qubit states
- **GHZ States**: Multi-qubit entangled states (up to 100 qubits)
- **Pauli Operators**: Z, X, Y operators and their expectation values
- **Quantum Decoherence**: How noise affects quantum states
- **Error Mitigation**: Techniques to improve results on noisy quantum hardware
- **Transpilation**: Circuit optimization for real quantum processors

## Requirements

```
qiskit
qiskit-ibm-runtime
qiskit-aer
matplotlib
numpy
```

## Hardware

Experiments are designed to run on:
- IBM Quantum simulators (Aer)
- IBM Quantum real hardware (127-qubit processors)
