# Bell’s Inequality Experiment - Quantum Entanglement Simulation

This project simulates Bell’s Inequality Experiment using Qiskit to test quantum entanglement and verify Bell’s theorem.

## Overview

Bell’s theorem states that quantum mechanics predicts correlations that cannot be explained by classical physics. This experiment:

- Generates an entangled Bell pair.

- Measures the qubits at different angles.

- Computes correlation values.

- Tests Bell’s inequality using the CHSH parameter.

## Dependencies

Ensure you have the following installed:

- pip install qiskit numpy qiskit-aer

## Running the Experiment

Execute the script using:

``` python Bell's_inequality_simulation.py``` 

## Expected Outcome

- If Bell’s inequality is violated (|S| > 2), quantum entanglement is confirmed.

- If |S| ≤ 2, results align with classical physics.

## Code Explanation

- Bell Pair Creation: Uses Hadamard and CNOT gates.

- Measurement in Different Bases: Rotates qubits to selected measurement angles.

- Simulation & Correlation Calculation: Runs the experiment on a quantum simulator and evaluates results.

- Bell’s S Calculation: Computes the CHSH inequality to test quantum correlations.

## References

Qiskit Documentation

Bell’s Theorem - Wikipedia
