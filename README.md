# Examination Hall Seating Allocation Simulator

Course: Solving Problems Using Modelling and Simulation (SPMS) - NEC00091

Team:
- Krishna Shrivastava (BTEC25O1031)
- Aditya Mishra (BTEC25O1003)

## About
A Python simulation that seats students in exam halls so that no two students
writing the same paper sit next to each other. Three strategies are compared:
sequential, random (Monte Carlo, 500 trials) and optimised (Simulated Annealing).

## Results (200 students, 5 halls, 240 seats)
| Strategy | Conflicts |
|---|---|
| Sequential | 308 |
| Random (mean) | 61.2 |
| Optimised | 0 |

## Requirements
pip install numpy matplotlib

## How to run
python exam_seating_simulator.py
python exam_seating_simulator.py --find ECE-001

Or open exam_seating_simulator.ipynb in Jupyter and run all cells.

## Files
- exam_seating_simulator.py - main program
- exam_seating_simulator.ipynb - Jupyter notebook version
- Exam_Seating_Simulator_PPT.pptx - presentation
- output/ - graphs and seating_plan.csv
