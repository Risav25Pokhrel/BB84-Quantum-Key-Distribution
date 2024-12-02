# QKD BB84 PROTOCOLS

## Overview

This repository is dedicated to exploring the **BB84 Quantum Key Distribution (QKD) Protocol**, the first-ever QKD protocol, published in 1984 by Charles H. Bennett and Gilles Brassard. BB84 is a revolutionary method for securely communicating a private key using quantum mechanics principles.

The repository includes:
- A detailed PDF explaining the BB84 protocol and its associated concepts.
- Code implementation of the BB84 protocol, including potential eavesdropper scenarios.

---

## Contents

### 📄 **QKD BB84 PROTOCOLS.pdf**
This document provides:
- A brief introduction to quantum cryptography.
- Insights into private key methods and basic cryptographic techniques (e.g., Caesar cipher).
- A detailed explanation of BB84 and E91 protocols.
- A step-by-step breakdown of the BB84 protocol, along with explanations of Eve's potential eavesdropping attacks.

### 📜 **Code Implementation**
The implementation details are provided in the linked [notebook](https://github.com/Risav25Pokhrel/BB84-Quantum-Key-Distribution/blob/main/QKD.ipynb), which covers:
- Simulation of the BB84 protocol.
- Eve's attack simulations (`interceptAndSend` and `entangleQubit` functions).
- A quantum entanglement approach to enhance security.

---

## BB84 Protocol: Key Highlights
1. **Quantum Principles:**
   - Relies on Heisenberg's Uncertainty Principle.
   - Any attempt to gain information disrupts the quantum state.

2. **Security Conditions:**
   - Non-orthogonal quantum states ensure information gain is detectable.
   - An authenticated classical communication channel is required.

3. **Eavesdropping Scenarios:**
   - `interceptAndSend(circuit)`: Simulates qubit interception and re-encoding.
   - `entangleQubit(circuit)`: Models qubit entanglement by an eavesdropper.

---

## References
- **Documentation:** Read the full explanation in the `QKD BB84 PROTOCOLS.pdf`.
- **Code Notebook:** [BB84-Quantum-Key-Distribution](https://github.com/Risav25Pokhrel/BB84-Quantum-Key-Distribution/blob/main/QKD.ipynb).

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Risav25Pokhrel/BB84-Quantum-Key-Distribution.git
   ```
2. Open the `QKD BB84 PROTOCOLS.pdf` for theoretical understanding.
3. Run the code in the provided notebook to simulate the BB84 protocol and analyze its security.

---

**Maintained by**  
**[Risav Pokhrel](https://github.com/Risav25Pokhrel)**  
