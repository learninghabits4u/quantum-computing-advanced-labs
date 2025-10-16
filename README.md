# Quantum Computing Understanding (Advanced Labs)
**Purpose:** Build deep intuition about qubits, superposition, interference, entanglement, teleportation, and state visualization. This notebook contains step-by-step explanations, runnable code (Qiskit), and exercises for each lab.

**Pre-requisites:** Python 3.9+, install dependencies:
```
pip install qiskit qiskit-aer matplotlib numpy
```

## Lab 1.1 — Multi-qubit Superposition & Interference

**Objective:** Create multi-qubit superposition states, apply phases, and observe interference patterns. We will use a 3-qubit example and step through how phase rotations change measurement probabilities.

## Lab 1.2 — GHZ vs W states (3-qubit entanglement)

**Objective:** Prepare GHZ and W states, compare their measurement statistics and robustness to qubit loss.

**Theory summary:**
- GHZ: (|000> + |111>)/√2 — strong global correlations; if one qubit is lost, entanglement collapses.
- W: (|001> + |010> + |100>)/√3 — remains partially entangled if one qubit is lost.


## Lab 1.3 — Quantum Teleportation (complete, with classical correction)

**Objective:** Teleport an arbitrary single-qubit state from qubit 0 to qubit 2 using an entangled pair and two classical bits. We'll demonstrate the full flow and verify by statevector comparison (deterministic on simulator).

## Lab 1.4 — Bloch-sphere visualization & measurement in different bases

**Objective:** Visualize single-qubit states on the Bloch sphere and perform measurements in X and Y bases.


