# Kyber-PQC-Accelerator
A hardware accelerator for the **Kyber** post-quantum cryptography (PQC) algorithm integrated with the **Microwatt open-source CPU core**, designed for secure key exchange in the era of quantum computing.

## Project Proposal
This project focuses on implementing the **Kyber algorithm** as a **hardware accelerator** on the **Microwatt CPU**. Kyber is a quantum-resistant encryption scheme, part of the **post-quantum cryptography (PQC)** family, which provides secure key exchange against future quantum computer attacks.

### Key Objectives
- **Kyber Algorithm Implementation**: Build a hardware accelerator for **key generation**, **encryption**, and **decryption** operations of the Kyber algorithm.
- **Integration with Microwatt**: Implement this accelerator as a part of the Microwatt CPU to enable efficient, quantum-safe key exchange in a low-power, area-efficient manner.
- **Software Control**: Develop software drivers to interact with the hardware accelerator, providing control over cryptographic operations.

### Why Kyber?
Kyber is a lattice-based **key encapsulation mechanism (KEM)** that is designed to be resistant to attacks from quantum computers. This makes it a strong candidate for securing communications in the post-quantum era. By implementing Kyber on Microwatt, we aim to provide a hardware-accelerated solution that is both **power-efficient** and **quantum-safe**, making it ideal for embedded systems and edge devices.

## Implementation Details
1. **Modules**
   - **Polynomial Arithmetic**: Efficient implementation of polynomial multiplication and modular reductions required for Kyber.
   - **Key Generation**: Design hardware to generate public and private keys.
   - **Encryption/Decryption**: Implement the encryption and decryption procedures.
   - **CPU Interface**: Create the interface between Microwatt CPU and the Kyber accelerator.

2. **Development Tools**
   - **Simulation**: Use tools such as **Verilator** and **Yosys** for hardware simulation.
   - **Microwatt Integration**: Use the open-source Microwatt project and tools such as **GCC** for POWER to integrate the hardware accelerator with the CPU.

3. **Testing and Verification**
   - **Testbenches** for hardware verification.
   - **Software Drivers** to interact with the hardware and perform full key exchange operations.

## Timeline
1. **Week 1**: Understand the Kyber algorithm and begin setting up the development environment.
2. **Week 2**: Implement the **polynomial arithmetic** module and test.
3. **Week 3**: Develop the **key generation** and **encryption** modules.
4. **Week 4**: Integrate modules into the Microwatt CPU and begin testing key exchange.
5. **Week 5**: Final testing and debugging.
6. **Week 6**: Finalize documentation, GitHub repo, and prepare submission.

## License:
This project is licensed under the **MIT License**.

