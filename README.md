# Quantum Random Number Generator (QRNG)

## Overview
As a first-year student in Cybersecurity and Cloud Computing, I built this project to explore the intersection of **Quantum Mechanics and Cryptography**. 

Classical computers generate *pseudo-random* numbers using deterministic algorithms. In cybersecurity, predictability is a vulnerability. This project leverages **Qiskit** to build a Quantum Random Number Generator (QRNG) that produces **true, physically unpredictable randomness** using quantum superposition.

## How it works
1. **Superposition:** We apply a **Hadamard gate** to a set of Qubits initialized at `|0⟩`. This places each qubit in a perfect superposition state `(|0⟩ + |1⟩) / √2`.
2. **Measurement:** According to the laws of quantum mechanics, measuring this state forces the qubit to collapse into a `0` or a `1` with exactly a 50/50 probability.
3. **Conversion:** The resulting quantum bit string (e.g., `1011`) is converted into a classical decimal integer.

## Technologies Used
* **Python 3**
* **IBM Qiskit** (Quantum circuit design & simulation)
* **Qiskit Aer** (Local execution)
* **Matplotlib** (Circuit visualization)

## How to run it locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/lusbustus/Quantum-RNG-Cryptography.git](https://github.com/lusbustus/Quantum-RNG-Cryptography.git)
