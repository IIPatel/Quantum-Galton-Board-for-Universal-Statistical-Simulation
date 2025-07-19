# Quantum-Galton-Board-for-Universal-Statistical-Simulation

This project addresses one of the WISER 2025 Quantum Projects to develop resource-lean quantum algorithms for Monte Carlo-like statistical simulations, specifically focusing on the implementation and generalization of a Quantum Galton Board (QGB) as a "Universal Statistical Simulator."

## Team Information

* **Team Name:** Quarx
* **Team Member:**
    * **Ibrahim Patel** [*WISER Enrollment ID:* **gst-LargptvrK1NQ1t**]

## Project Summary 

Classical Monte Carlo methods, while powerful, suffer from slow convergence rates, making high-fidelity simulations computationally expensive. Quantum walks, the quantum analogue of classical random walks, offer a potential quadratic speedup by leveraging quantum phenomena such as superposition and interference.

This solution is based on the Quantum Galton Board (QGB) circuit design proposed by Carney and Varcoe in [Universal Statistical Simulator (arXiv:2202.01735v1)](https://arxiv.org/abs/2202.01735v1). This framework intuitively models the probabilistic branching of a classical Galton board, where a "ball" (represented by a single excitation in a quantum register) traverses layers of "pegs" (implemented via controlled-SWAP and CNOT gates controlled by a superposition qubit). The QGB generates a probability distribution at its output, which, for an unbiased setup, approximates a binomial distribution and, through post-processing (summing blocks of outcomes), converges to a Gaussian distribution.
