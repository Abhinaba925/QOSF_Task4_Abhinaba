# QOSF_Task4_Abhinaba
## Introduction
The Swap test is a mathematical technique for testing how alike two quantum states are. This test is also a useful test for entanglement of pure states. Swap test is also widely used in quantum machine learning. 

## Depolarization and error mitigation
Depolarization error in qubits is a specific type of noise or error that affects the reliability and accuracy of quantum computations performed on qubits.
Depolarization errors in qubits can be caused by various factors, including environmental interference, electromagnetic radiation, temperature fluctuations, and interactions with nearby particles. These external influences can disrupt the quantum coherence of qubits. Depolarization errors are often mathematically represented as a depolarizing channel. This channel acts probabilistically, randomly applying Pauli X, Y, or Z gates to the qubit with some probability. These Pauli gates introduce errors and cause the qubit's state to evolve in an unpredictable manner. The severity of depolarization error is quantified by an error rate. This rate represents the probability that a qubit will experience a depolarizing error during a quantum operation. Lower error rates are desired for achieving high-fidelity quantum computations. In this task, I have used error rate upto .5 starting from 0.01 in a step of 0.0098. To mitigate the impact of depolarization errors and enhance the reliability of quantum computations, quantum error correction codes are used. These codes involve encoding quantum information redundantly to detect and correct errors that occur during quantum operations.

## References 
* Foulds, Steph, et al. "The Controlled SWAP Test for Determining Quantum Entanglement." Quantum Science and Technology, vol. 6, no. 3, 2021, p. 035002. DOI: 10.1088/2058-9565/abe458.
* Vovrosh, Joseph, et al. "Simple Mitigation of Global Depolarizing Errors in Quantum Simulations." Physical Review E, vol. 104, 2021, p. 035309. DOI: 10.1103/PhysRevE.104.035309.  
* https://quantumcomputinguk.org/tutorials/introduction-to-the-swap-test-in-qiskit-with-code
* Bombin, H., et al. "Strong Resilience of Topological Codes to Depolarization." Physical Review X, vol. 2, 2012, p. 021004. DOI: 10.1103/PhysRevX.2.021004.
