# PROJECT PROPOSAL

## Kyber-PQC-Accelerator
A hardware accelerator for the **Kyber** post-quantum cryptography (PQC) algorithm integrated with the **Microwatt open-source CPU core**, designed for secure key exchange in the era of quantum computing.

## DESCRIPTION
This project focuses on implementing the **Kyber algorithm** as a **hardware accelerator** on the **Microwatt CPU**. Kyber is a quantum-resistant encryption scheme, part of the **post-quantum cryptography (PQC)** family, which provides secure key exchange against future quantum computer attacks.

### PROJECT OBJECTIVES
- **Kyber Algorithm Implementation**: Build a hardware accelerator for **key generation**, **encryption**, and **decryption** operations of the Kyber algorithm.
- **Integration with Microwatt**: Implement this accelerator as a part of the Microwatt CPU to enable efficient, quantum-safe key exchange in a low-power, area-efficient manner.
- **Software Control**: Develop software drivers to interact with the hardware accelerator, providing control over cryptographic operations.

### MOTIVATION
Kyber is a lattice-based **key encapsulation mechanism (KEM)** that is designed to be resistant to attacks from quantum computers. This makes it a strong candidate for securing communications in the post-quantum era. By implementing Kyber on Microwatt, I aim to provide a hardware-accelerated solution that is both **power-efficient** and **quantum-safe**, making it ideal for embedded systems and edge devices.

## IMPLEMENTATION 
1. **Design**
   - **Polynomial Arithmetic**: Efficient implementation of polynomial multiplication and modular reductions required for Kyber.
   - **Key Generation**: Design hardware to generate public and private keys.
   - **Encryption/Decryption**: Implement the encryption and decryption procedures.
   - **CPU Interface**: Create the interface between Microwatt CPU and the Kyber accelerator.

2. **Testing and Verification**
   - **Testbenches** for hardware verification.
   - **Software Drivers** to interact with the hardware and perform full key exchange operations.


## TIMELINE OF THE PROJECT

• Week 1 - Study Kyber and set up development environment  
• Week 2 - Implement and test polynomial arithmetic module  
• Week 3 - Build key generation and encryption modules  
• Week 4 - Integrate with Microwatt and test key exchange  
• Week 5 - Final testing and debugging  
• Week 6 - Complete documentation and prepare submission  
