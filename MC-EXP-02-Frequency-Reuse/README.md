📡 Game-Based Cellular Frequency Reuse Visualizer

🎯 Aim :

To understand the cellular frequency reuse concept and determine the co-channel cells for a selected cell using an interactive game-based visualization tool.

📖 Theory :

In cellular communication systems, frequency reuse is used to improve spectrum efficiency. The cluster size is calculated using:

𝑁 = 𝑖² + ij + j²

Where:

i = shift in one direction

j = shift in 60° direction

N = cluster size

Co-channel cells are separated by reuse distance:

𝐷 = R ✓3 N​

Where:

R = cell radius

🛠 Technologies Use :

Python

Tkinter (GUI)

Math Library

Object-Oriented Programming

🎮 Game-Based Features :

Interactive hexagonal grid

User selects a reference cell

System calculates possible co-channel cells

User guesses co-channel cells

Correct selection → Green

Incorrect selection → Red

Final visualization with connecting lines

Restart option using Shift + R

📊 Working Procedure :

Run the program

Enter values of i and j

Cluster size N is calculated

GUI opens with hexagonal grid

Select one cell

Identify and select co-channel cells

Application validates selections

Lines show reuse distance pattern

📚 Learning Outcomes :

Understanding cellular network design

Frequency reuse principle

Co-channel interference

Cluster size calculation

Visualization of reuse distance
