# QOSF-Mentorship-Program

## Quantum Circuit Experiment

This project contains a Python script to create and simulate quantum circuits using Qiskit. It includes setting up a quantum circuit with defined parameters, normalizing state amplitudes, and potentially visualizing results.

### Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

### Installation

1. Install [Qiskit](https://qiskit.org/) for quantum circuit design and simulation:
   ```bash
   pip install qiskit
   ```
2. Update and install Qiskit-Aer for quantum simulation:
   ```bash
   pip install -U qiskit-aer
   ```
   
### Usage

1. Set the parameters:
   - `size`: Number of qubits in the circuit.
   - `state_values`: Define the initial state values for circuit configuration.
   - `target_amplitude`: Normalized amplitude for the states.

### Examples

Here is a minimal example of running the script with different values:
```python
size = 5
state_values = [22, 17, 27, 12]
target_amplitude = 0.5 / np.sqrt(len(state_values))
```
