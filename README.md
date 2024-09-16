# Vehicle-Routing-Project
This was the final project for the discrete optimisation and decision making module of my master's degree in data science

## DESCRIPTION
This project was to use decrete mathamatics to define a vehicle routing problem. In this problem multiple peole have to travel around "Verona" and complete a set of tasks to do this they can travel between nodes by walking, cycling or catching the bus. When cycling they must hire a bike from a hire node and then deposit the bike at another node. They nodes must have bikes at the time of hire and have space for a new bike when it is being dropped off. Buses can only be caught at certain times. Both these services cost money, which is limited by each person's budget. Some tasks also have time windows that must be adhered to.

The vast majority of this wasmy own work.

The repository contains:
-  The documentation can be found in the pdf document called DODM Project Documentation. The document contains the mathematical model definition, assumptions and a theorical metaheuristic adaptation of the problem.

- Some files of interest:
    * function to import the problem inputs -> import_function.py
    * model implementation -> run_scenario.py
    * over arching method to solves the problem -> main.py
    * incomplete visualisation tool -> Resources\visualisation methods.py
    * example outputs can be found in folder: outputs\

## DEPENDENCIES
- A Gourobi license
- The installation of following libraries: sys, math, random, itertools, os, datetime, pathlib gourobipy, numpy.lib, pandas, numpy, copy, matplotlib.pyplot, matplotlib.gridspec, pickle
- The model was created to work with an older version of python (likely 3.9)

