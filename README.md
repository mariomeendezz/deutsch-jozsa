# Deutsch and Deutsch–Jozsa Algorithms (Qiskit)

This project implements the **Deutsch** and **Deutsch–Jozsa** quantum algorithms using **Qiskit**.

The objective of this project is **not** to provide an in-depth theoretical explanation of the algorithms, but to **implement them in practice**, simulate their execution, and **verify their correct behavior** when distinguishing **constant** and **balanced** Boolean functions.

---

## Project structure

- `notebooks/`  
  Contains the main Jupyter notebook with the full implementation and simulations.

- `figures/`  
  Contains the figures generated in the notebook (quantum circuits), saved for visualization without re-running the code.

---

## Project goals

- Implement the **Deutsch algorithm** (1 input qubit)
- Implement the **Deutsch–Jozsa algorithm** (n input qubits)
- Construct valid **constant** and **balanced** oracle circuits
- Simulate the algorithms using **Qiskit Aer**
- Verify that the measurement outcomes correctly distinguish constant from balanced functions

---

## Requirements

Install the required Python packages with:

```bash
pip install -r requirements.txt
```

---

## License

This project is licensed under the MIT License.
