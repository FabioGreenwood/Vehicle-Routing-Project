# Vehicle-Routing-Project
This was the final project for the discrete optimisation and decision making module of my master's degree in data science

## DESCRIPTION
This project was to use decrete mathamatics to define a vehicle routing problem. In this problem multiple peole have to travel around "Verona" and complete a set of tasks to do this they can travel between nodes by walking, cycling or catching the bus. When cycling they must hire a bike from a hire node and then deposit the bike at another node. They nodes must have bikes at the time of hire and have space for a new bike when it is being dropped off. Buses can only be caught at certain times. Both these services cost money, which is limited by each person's budget. Some tasks also have time windows that must be adhered to.

The vast majority of this was my own work.

## Navigation

This project was carried out in an orderly fashion, while likely not up to professional standards, the method "run_scenario" within run_scenario.py has a structure which follows the structure of the documentation, with text blocks (e.g. """ contents """) matching the sections within the documentation.docx, good commenting and the constraints being assigned abbreviated references, example: "#BTC3_lin" noting that this is the third constraint defined in the "Bus Travel Constraints" subsection within the word doc.

The repository contains:
-  The documentation can be found in the pdf document called "Discrete Optimisation Project Documentation". The document contains the mathematical model definition, assumptions and a theorical metaheuristic adaptation of the problem.

- Some files of interest:
    * function to import the problem inputs -> import_function.py
    * model implementation -> run_scenario.py
    * over arching method to solves the problem -> main.py
    * incomplete visualisation tool -> Resources\visualisation methods.py
    * example outputs can be found in folder: outputs\

## DEPENDENCIES
- A Gurobi license
- The installation of following libraries: sys, math, random, itertools, os, datetime, pathlib gourobipy, numpy.lib, pandas, numpy, copy, matplotlib.pyplot, matplotlib.gridspec, pickle
- The model was created to work with an older version of python (likely 3.9)

