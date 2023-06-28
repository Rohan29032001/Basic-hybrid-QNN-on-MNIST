# Basic-hybrid-QNN-on-MNIST
We use Qiskit and PyTorch to build a hybrid Quantum Neural Network for classifying images of handwritten digits of 4 vs 9. We classify 4 vs 9 as they are the most identical in appearance. The outermost fully connected layer of the neural network is connected to a quantum layer. This quantum layer consists of a 4-qubit circuit with Haddamard. Ry gates and some CNOTs to entangle the qubits. The resulting test accuracy is 99%.
