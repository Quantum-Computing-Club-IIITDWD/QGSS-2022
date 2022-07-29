# QGSS-2022 - Practice for club activity.

The Qiskit Global Summer School 2022, is a summer school program consisting of 4 Lab problems set by IBM Quantum.

## Labs

### Lab 1

Intro to circuit composition and cost
In the first Lab we will start slowly by giving an introduction to simple one qubit gates and show how they can be seen as rotations. We will then take a look at multi qubit gates and see some examples on how they can be used to create entangled states. After that we will apply the knowledge of complexity theory, which we learned in class, to quantum circuits. We will also take another look at the Quantum Fourier Transform as well as how to generate entangled states, with complexity theory in mind.

This lab is meant as an introduction / a repetition of the basics of quantum computation, as well as for introducing some examples of the concepts shown in the lecture to help you to learn them.

<a href = "https://github.com/Quantum-Computing-Club-IIITDWD/QGSS-2022/blob/main/QGSS22-lab-1.ipynb"> Click Here to see Lab 1 </a>

### Lab 2

Advanced circuits
The formalism of quantum information theory can look rather abstract compared to the circuit model of quantum computation. The Qiskit Opflow module aims to bridge the language of quantum information theory with the framework of circuits that is used to run experiments. This will make it seamless to switch back and forth between theoretical ideas and their experimental implementation.

One example that we'll see in some detail is the simulation of the time-evolution of quantum system. Using the Qiskit Opflow module going from the definition of the Hamiltonian governing the dynamics of the system to the experiment implementing a quantum simulation of the dynamics can be done in just a few lines of code!

<a href = "https://github.com/Quantum-Computing-Club-IIITDWD/QGSS-2022/blob/main/QGSS22-lab-2.ipynb"> Click Here to see Lab 2 </a>

### Lab 3

Quantum Noise
Noise is the omnipresent evil that corrupts our quantum computers. In this lab we will delve deeper in the details of the various kinds of noise affecting our computation to build a better understanding of them. We'll also look at some simple techniques we can use to fight the noise and recover the results we were looking for!

The different facets of the quantum noise that we'll encounter in this lab are: projection noise, measurement noise, coherent noise and incoherent noise. Projection noise is the noise caused by finite sampling of the wavefunction. Measurement noise is the noise affecting the physical measurement process, which is not perfect. Coherent noise is a type of noise, like over-rotation, which has a deterministic effect on our operations while incoherent noise is a non-deterministic noise which "scrambles" the quantum information in the quantum state.

<a href = "https://github.com/Quantum-Computing-Club-IIITDWD/QGSS-2022/blob/main/QGSS22-lab-3.ipynb"> Click Here to see Lab 3 </a>

### Lab 4

Simulate a Quantum Spin-1/2 Model
One of the leading uses for quantum computers will be to simulate quantum systems such as molecules or engineered materials. Actually executing a quantum simulation on a current quantum computer, however, can be difficult and error prone. Your objective for this lab is to complete the simulation exercises and then improve on them to get the highest state tomography score.

<a href = "https://github.com/Quantum-Computing-Club-IIITDWD/QGSS-2022/blob/main/QGSS22-lab-4.ipynb"> Click Here to see Lab 4 </a>

## Instructions

To execute the given file, first you need to install Qiskit (assuming you have python3 installed).
To do so use:

```
pip install qiskit
```

Later clone the repository in your local system or any cloud system you might be using( like google colab)

To clone use:
 ```
 git clone https://github.com/Quantum-Computing-Club-IIITDWD/QGSS-2022.git
 ```
After getting all the files on your local system try to execute the ipynb file and go through the tutorials.
Fill in the code were the questions are asked to solved while rest are for learning purpose.


For any Query mail to qcclub@iiitdwd.ac.in

Enjoy Learning Quantum!

