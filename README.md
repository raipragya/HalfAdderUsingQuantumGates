Half Adder Implementation Using Quantum Gates

This project demonstrates the implementation of a half adder using quantum gates in a quantum computing framework. A half adder is a basic digital circuit that computes the sum and carry of two binary bits.
Quantum Gates Used:

    CCX (Toffoli Gate): A controlled-controlled NOT gate used to compute the carry bit in the quantum circuit.
    NOT (X Gate): A quantum gate that flips the state of a qubit (|0⟩ ↔ |1⟩).
    Pauli-X Gate: Another name for the NOT gate, used to manipulate the qubits.

Circuit Design:

    Input Qubits: Two input qubits represent the binary bits to be added.
    Output Qubits:
        One qubit for the sum (XOR operation of the two inputs).
        One qubit for the carry (AND operation of the two inputs).
    Quantum Gates Configuration:
        The Pauli-X and NOT gates are used to compute the XOR operation for the sum output.
        The CCX (Toffoli Gate) is used to compute the AND operation for the carry output.

Features:

    Utilizes quantum gates to simulate the behavior of a classical half adder.
    Demonstrates the capability of quantum circuits to perform basic arithmetic operations.
