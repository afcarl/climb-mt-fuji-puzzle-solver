# Climb Mt. Fuji Puzzle Solver

A script that solves 	Karin & Jürg von Känel's sliding block puzzle called "[Climb Mt. Fuji](http://www.woodpuzzles.com/Puzzles/ClimbMtFuji/ClimbMtFuji.html)."  
The script solves it in 34 moves, 6 fewer than the solution included with the game.

---

The puzzle is interesting because it has a second layer of wood that makes some moves impossible.

![The puzzle](http://www.woodpuzzles.com/Puzzles/ClimbMtFuji/ClimbMtFuji.640x640.png)

The goal is to get the climber from the bottom to the top as shown below.

![The goal](http://www.woodpuzzles.com/Puzzles/ClimbMtFuji/ClimbMtFuji_Goal.450x308.png)

[Climb Mt. Fuji Solver.ipynb](Climb%20Mt.%20Fuji%20Solver.ipynb) 
contains the code to generate the solution and [block.csv](block.csv) is a manually constructed CSV file
specifying how the different pieces can block each other from moving.
