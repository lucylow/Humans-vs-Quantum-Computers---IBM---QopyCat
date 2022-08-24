# < QopyCat | Schrödinger Quantum Cats >
Womanium Quantum Hackathon 2022

![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/Screen%20Shot%202022-08-23%20at%207.54.19%20PM.png?raw=true)

Name of Team:
Name of team member: Lucy Low low.lucyy@gmail.com, lucylow github, discord
Name of pitch presenter: Lucy Low
Name of Challenge: Humans-vs-Quantum-Computers


Game that teaches quantum computing using Qiskit (http://qiskit.org) 


Quantum Teleportation built using IBM's QisKit SDK to create quantum computing circuits.
Taking advantage of IBM's public facing 5 qubit quantum computer

To learn some of these basic quantum concepts for yourself, check out the first few sections of the textbook Learn Quantum Computation using Qiskit. The first chapter starts off quite gently, without assuming too much background mathematical knowlege.


# Staying Alive: Storyline

Shipping a cat to Schrödinger. Better make sure it survives!


Good cat v.s. Bad cat.

![](https://github.com/lucylow/Humans-vs-Quantum-Computers---IBM---QopyCat/blob/main/data/Screen%20Shot%202022-08-23%20at%207.56.55%20PM.png?raw=true)

Bad cat is an obnoxious cat who, sickly, gets off on copying, imitating, emulating, simulating and miming all your actions. She is just another individual who copies you in everything you do.

In the dawn of the Quantum Era, a primitive 3-qubit Quantum Computer is trying to challenge the Classical Computer, the long-time ruler of the Computer Empire. Your mission is to use your Human Intelligence to help the Quantum Computer defeat the Classical Computer and demonstrate "quantum supremacy" for the first time in human history. The battle field of the Quantum-Classic war is none other than the classic Pong game.



This is a quantum puzzle game in which you have to save both the good and bad cat in the screen at the same time, in order to earn quantum gates to complete the quantum circuit. 


# How it works 

This is a tile-based puzzle game with a quantum physics twist. You control a cat in a superposition through a bizarre world. 



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

Save the world with quantum circuits. 

gamification of science: When making a quantum-related game, you can choose one of two paths: either you implement a quantum technique like procedural generation of maps, or you take an educational approach. 

You win by solving quantum circuit puzzles. 

-Move with WASD or arrow keys. 

-Avoid lethal yellow lasers.

-Use blue detector lines to your advantage by briefly collapsing the superposition.

-Move both cats into the cardboard boxes to clear the level.

-There might be other things that exist in superposition as well.

-Press "R" if you get stuck.


1. The game begins when N players.
2. The initial and final quantum states are given.
3. Player completes QopyCat maze to unlock Quantum Gate Cards
4. The players drag and drops the Quantum Gate Cards to make a correct quantum circuit for the problem. 
5.  Select a gate or tool from the popup menu (that appears when pressing the Enter key). Place a gate on an empty white block in the circuit (using the X key or button)
6. The user circuit converter transforms the user input circuit into a Qiskit quantum circuit.
7. At the end of the round, measurements are taken of the quantum circuit. (The “constant” player wins if the measurement turns out to be 00 or 11, and the “balanced” player wins if the measurement turns out to be 01 or 10. )
8. The FIRST player who gets the correct quantum circuit in the shortest amount of time WINS!

# Maps  Level Systems

Increasing Difficulty:

1. Normal
2. Medium
3. Standard
4. Average
5. Intermediate

# Gate Cards

Gate cards will consist of either single qubit gates or two qubit gates, and each gate is assigned a rarity that determines how frequently it is drawn. The gate cards are as follows:

1. Measurement (ends the game early) (Legendary)
2. U3 (Epic)
3. SWAP (Rare)
4. CX, CY, CZ, CH (Rare)
5. RX, RY, RZ (Rare)
6. I, S, T (Uncommon)
7. S_dg, T_dg (Uncommon)
8. H (Common)
9. X, Y, Z (Common)


# Quantum Teleportation: Build the Circuit

Explore the building blocks of quantum gates and quantum mechanics through puzzles.

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


# Future Plans
* Add game mechanics like portals and powerups
* Add quantum wall barrier to change good/bad cat relative positions
* Compare circuit execution on a classical computer vs real quantum device
* https://github.com/mxgmn/WaveFunctionCollapse
* Add different circuits like quantum error correction for the cat to get rid of quantum errors to keep our quantum state alive
* procedural generation like terrain, levels, puzzles, etc) for game content using quantum computing 



Have fun exploring and solving quantum circuit puzzles!
