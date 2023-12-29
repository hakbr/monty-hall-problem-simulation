# monty-hall-problem-simulator
# A bash computer simulator for the Monty Hall problem
# Monty Hall Problem Simulator

Overview
The "monty_hall_simulator.sh" script is a Bash script that simulates the Monty Hall Problem, a probability puzzle based on a game show scenario. The script runs a specified number of simulations (default: 10,000) to analyze the outcomes of two different strategies: keeping the original choice and switching the choice after a door is revealed.

Monty Hall Problem
The Monty Hall Problem is a probability puzzle based on a game show scenario. The player is presented with three doors. Behind one door is a prize, while the other two doors hide goats. The player makes an initial choice, and then one of the other doors, which has a goat behind it, is revealed. The player is then given the option to stick with their original choice or switch to the other unopened door.

Features
Simulation: Run a specified number of simulations to analyze the outcomes of the Monty Hall Problem.

Strategies: Evaluate two strategies - "keep" (keeping the original choice) and "switch" (switching the choice after a door is revealed).

Usage
Run the Script:

Save the script to a file, e.g., monty_hall_simulator.sh.
Make it executable: chmod +x monty_hall_simulator.sh.
Run the script: ./monty_hall_simulator.sh.
View Results:

The script will display the number of wins and losses for both the "keep" and "switch" strategies.

Example

$ ./monty_hall_simulator.sh
Keep strategy: 3332 wins and 6668 losses
Switch strategy: 6658 wins and 3342 losses

Customization
You can modify the num_sims variable in the script to change the number of simulations.

License
This project is licensed under the terms of the GNU General Public License version 3.0 (GPL-3.0).
