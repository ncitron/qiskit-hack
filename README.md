# How to get a quantum computer to play Battleship
### By the Duke Blue group for the 2020 Qiskit Community Summer Jam - North Carolina
### Brandon Weiss, Noah Citron, and Will Hamilton

To play game, go to http://quantumbattleship.com

This project allows the user to play battleship against a quantum computer. Using IBM Qiskit's open source software, we 
used Grover's Algorithm to have a quantum computer get a hit ~97.8% of the time. We also built an algorithm that randomly
places the computer's ships and an online interface to play the game. In the future, we plan to let the user watch a 
classical computer get absolutely dismantled by the quantum computer.

This project has a backend, a frontend, and an api connecting the two. The backend contains a quantum search algorithm
for the quantum computer in 'Grover Class.ipynb', a pseudo-random algorithm for ship deployment in 'Ship Placement.ipynb',
and a framework for a classical implementation to be used in the future in 'Classical Algorithm.ipynb'. The api is located
in 'setup.py'. The frontend contains javascript and css code that builds and runs the interface, giving the user intuitive
controls in the game such as clicking the grid to deploy ships and attack the computer.
