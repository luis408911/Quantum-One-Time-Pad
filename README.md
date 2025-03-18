# Quantum One-Time Pad Encryption using Quirk

## Overview
This project demonstrates the implementation of a **Quantum One-Time Pad (QOTP)** encryption protocol using the [Quirk Quantum Circuit Simulator](https://algassert.com/quirk). The primary goal is to securely transmit a classical message by utilizing quantum principles such as superposition, entanglement, and measurement.

---

## Features

### 🔹 Quantum Key Generation
- Used **Hadamard gates (H)** to place key qubits in superposition.
- Generated random key bits essential for secure encryption.

### 🔹 Message Encoding with CNOT Gates
- Applied **Controlled-NOT (CNOT)** gates to entangle message qubits with the key.
- Achieved message encryption by quantum entanglement.

### 🔹 Message Decoding and Measurement
- Applied a second set of **Hadamard gates (H)** to decode the key.
- Measured all qubits to extract the final key and decrypted message.

### 🔹 Eavesdropper Detection
- Any attempt to intercept or measure the qubits before decoding causes observable disturbances in the system, highlighting QOTP's inherent security advantages.

---

## Tools & Technologies
- **Quantum Gates:** Hadamard (H), Pauli-X (X), CNOT
- **Measurement Operations**
- **Simulator:** Quirk Quantum Circuit Simulator

---

## Key Takeaways
This project provided hands-on experience in:
- **Quantum Cryptography and Key Distribution**
- Visualizing and simulating quantum circuits
- Understanding the quantum advantage in secure communication

---

## How to View the Circuit
1. Visit [Quirk Quantum Simulator](https://algassert.com/quirk).
2. Recreate the circuit based on:
   - Hadamard gates on key qubits
   - CNOT gates connecting key qubits to message qubits
   - Second Hadamard gates to decode
   - Measurement gates on all qubits

### **Direct Circuit Link:**
[View My Completed Circuit](YOUR_EXPORTED_LINK_HERE)

Just replace `file:///Users/josezaragoza/Downloads/Quirk%20with%20Circuit%20-%204%20wires,%2013%20ops,%20HHXDetectControlReset%E2%97%A6X%E2%80%A6.html#circuit=%7B%22cols%22%3A%5B%5B%22H%22%2C%22H%22%2C%22XDetectControlReset%22%5D%2C%5B%22%E2%97%A6%22%2C1%2C%22X%22%5D%2C%5B%22H%22%2C%22H%22%5D%2C%5B%22%7C0%E2%9F%A9%E2%9F%A80%7C%22%2C%22%E2%97%A6%22%5D%2C%5B1%2C%22%7C0%E2%9F%A9%E2%9F%A80%7C%22%2C%22%E2%97%A6%22%5D%2C%5B1%2C1%2C%22%7C0%E2%9F%A9%E2%9F%A80%7C%22%2C%22%E2%97%A6%22%5D%5D%7D` with the exported URL from Quirk!

---

## License
This project is open for educational and non-commercial use.
