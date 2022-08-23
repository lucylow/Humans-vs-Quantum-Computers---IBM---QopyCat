# QopyCat Quantum Cats
Humans-vs-Quantum-Computers
Womanium Quantum Hackathon 2022

Game that teaches quantum computing using Qiskit (http://qiskit.org) 


Quantum Teleportation built using IBM's QisKit SDK to create quantum computing circuits.
Taking advantage of IBM's public facing 5 qubit quantum computer

# How it works 
What is a quantum circuit? https://www.youtube.com/playlist?list=PL1826E60FD05B44E4

A game for exploring and understanding quantum teleportation using quantum circuits with a drag-and-drop quantum circuit simulator.

This application first entangles two qubits which were initially in the state |00⟩. Then, compare the results by running the same circuit on a simulator and real quantum hardware at IBM.

# Quantum Teleportation: Build the Circuit

Build a QuantumCircuit composed of the two classical and quantum bits:



# Gameplay Examples 

GIF of basic game play

Quantum teleportation circuit with Bloch sphere displays (showing that the qubit at the top has ended up at the bottom):


#Prerequsites
Git
Node.JS
Python 3
Qiskit
IBMQ API token

# Installing 


Clone the repository.

> git clone https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/edit/main/README.md.git

Install the dev dependencies.

> cd QopyCat

Build the output.

> npm run build

> npm install

Install Jupyter (https://github.com/IBM/qiskit-sdk-py/blob/master/tutorial/sections/tutorial4developer.ipynb). Currently the program expects Jupyter to be installed in the same directory as this repo.

> Copy out/qopycat.html to wherever you want.

# Running 


Enter q_command and click the Save button.


# Future Plans

* Compare circuit execution on a classical computer vs real quantum device

Have fun exploring and solving quantum circuit puzzles!
