# QopyCat Quantum Cats
Humans-vs-Quantum-Computers
Womanium Quantum Hackathon 2022

Game that teaches quantum computing using Qiskit (http://qiskit.org) 


Quantum Teleportation built using IBM's QisKit SDK to create quantum computing circuits.
Taking advantage of IBM's public facing 5 qubit quantum computer

To learn some of these basic quantum concepts for yourself, check out the first few sections of the textbook Learn Quantum Computation using Qiskit. The first chapter starts off quite gently, without assuming too much background mathematical knowlege.




# How it works 
What is a quantum circuit? https://www.youtube.com/playlist?list=PL1826E60FD05B44E4

A game for exploring and understanding quantum teleportation using quantum circuits with a drag-and-drop quantum circuit simulator.

This application first entangles two qubits which were initially in the state |00⟩. Then, compare the results by running the same circuit on a simulator and real quantum hardware at IBM.

https://qiskit.org/textbook/preface.html


==========

To make a quantum game, you'll need to write quantum software. The basic unit of quantum software is the circuit. You can create and manipulate these in Python by using the Qiskit framework.

Qiskit https://qiskit.org/

Once you have your quantum software, you need to run it. For complex quantum circuits, the only option is to run it on actual quantum computers. Prototype examples of this quantum hardware are freely available at the IBM Quantum Experience. It is a cloud service, where you submit your quantum jobs to run in the IBM Quantum labs. Note that it will take at least a few minutes to get your results back, so the wait time would need to be taken into account in your game.

IBM Quantum Experience https://quantum-computing.ibm.com/

If your quantum circuits are not very complex, you can avoid the need to use real quantum hardware. Instead you can just emulate it on your laptop (or even your phone) using tools bundled in with Qiskit. This is what is done by the vast majority of games that have been made using Qiskit so far (such as QPong)

Qiskit Simulators https://qiskit.org/overview/#simulators


=====

The game needs a good understanding of how various probabilities interact, to be able to comprehend how the state collapses upon observation, which happens when the piece is either capturing or being captured, and decides the position of a piece in superposition. Game is a great way to demonstrate and understand quantum properties.


# How to play?

You win by solving quantum circuit puzzles. 

1. The game begins when N players.
2. The initial and final quantum states are given.
3. The players drag and drop the provided quantum gates to make a correct quantum circuit for the problem. Select a gate or tool from the popup menu (that appears when pressing the Enter key). Place a gate on an empty white block in the circuit (using the X key or button)
4. The user circuit converter transforms the user input circuit into a Qiskit quantum circuit.
5. The FIRST player who gets the correct quantum circuit in the shortest amount of time WINS!


# Quantum Teleportation: Build the Circuit

This 2-player game consists, starting from a 6-qubit circuit initialized at |+>|->|+>|->|+>|-> to measure as many |0> or |1> depending on which player you are.

One is allowed to use H, X, Z, and the controlled version of this last two gates to achieve that goal.

 
Build a QuantumCircuit composed of the two classical and quantum bits: Quantum teleportation circuit with Bloch sphere displays (showing that the qubit at the top has ended up at the bottom):

GIF of basic game play

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
