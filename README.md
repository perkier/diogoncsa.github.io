
# Table of contents

<!--ts-->
   * [Energy Related projects:](#energy-related-projects)
      * [Promoting Energy and Economic Empowerment with Python](#promoting-energy-and-economic-empowerment-with-python)
      * [Micro-Grids Project](#micro-grids-project)
      * [CFD Machine Learning Module](#cfd-machine-learning-module)
      * [Data Science in Heat Transfer](#heating-fluid-selection)
<!--te-->


<!--ts-->
   * [Aeronautics Projects:](#aeronautics-projects)
      * [Airfoil Performance and Range](#airfoil-performance-and-range)
      * [CFD Result Analysis - Mesh Independance](#cfd-result-analysis---mesh-independance)
<!--te-->


<!--ts-->
   * [Marketing Projects:](#marketing-projects)
      * [Twitter Sentiment Analysis](#twitter-sentiment-analysis)
<!--te-->      

  
<!--ts-->
   * Search by Technologies:
      * [Automation](#airfoil-performance-and-range)
      * [Data Augmentation](#cfd-machine-learning-module)
      * [Data Manipulation](#promoting-energy-and-economic-empowerment-with-python)
      * [Data Visualization](#airfoil-performance-and-range)
      * [Deep Learning Classification](#twitter-sentiment-analysis)
      * [Deep Learning Regression](#cfd-machine-learning-module)
      * [Machine Learning Regression](#cfd-machine-learning-module)
      * [Monte Carlo Method](#micro-grids-project)
      * [Natural Language Processing](#twitter-sentiment-analysis)
      * [Polynomial Regression Curve Fitting](#heating-fluid-selection)
      * [Reinforcement Learning](#micro-grids-project)
      * [Simulation](#airfoil-performance-and-range)
      * [Unit-Testing](#tests)
      
      &nbsp;


[Contacts](#lets-talk)

<!--te-->

---


# Energy Related Projects
I am a climate activist. (...)


## Promoting Energy and Economic Empowerment with Python

Data Transformation and Machine learning

### Project Info
I created a tool to do solar power simulations over a 20 year time and tested it on my city, Porto, with several values of electricity average monthly bills. The goal is to give, for each average monthly bill, the best solar solution (which and how many solar panels, if a battery, and which battery, would be a good idea) to maximize the return of the investment.

The report was published by [Towards Data Science](https://github.com/).

The most important parts of the code can be viewed [here](https://github.com/perkier/Perkier.Energy).

### Technologies Used
- Code written in python 
- Data-Science libraries such as Pandas, sklearn and numpy, 
- Solar PV library PVlib; 
- Web Scrapping Library - Beautiful Soup;
- Machine Learning techniques to fit a consumption function curve to functions with different regression degrees were run and the degree with less error was found.

### Results

It was proven that solar panels can be a great long-term investment and batteries can make that investment even more profitable.
We can draw a line between the number of watts hour consumed during a time period and the number of solar panels that your house should need. The number of panels installed should be able to generate that power at the same time period. That way, the solar installation will generate 200% emotional profit and 400% of real, monetary, profit.

Renewable energies can be a great way to empower new generations of people. Saving, at average, 620€ per year can be a big leap forward in people’s lives and with smart investments, the money saved on the electrical bill can become a game changer to entrepreneurs and companies.


## CFD Machine Learning Module 

Data Science tools to handle and prepare the data; Machine Learning Regression; Deep Learning Regression;

### Project Info
Computational Fluid Dynamics (CFD) is (...). Such precision and complexity requires computational time. With enough data it is possible to generalize the previous simulations to other cases. I built a module that makes easier for a team to predict the other results of CFD simulations.

A module that does:
1. Pre-Processing of the data such as reading and compiling the data, feature scaling, splitting the data, defining training sets, etc. ;
2. Chooses the best Machine Learning Module to use and choses the best hyper parameters to use;
3. Interprets the data from the hyperparameters selection;
4. Creates a Machine Learning Playground where the data is fitted in a selected model (this model can be selected or choosen automaticly via the module calculations);
5. Tests the data and gives visual comparisson with previous simulation results;

### Technologies Used
- Coded in python 
- Data-Science libraries such as pandas and numpy
- Machine learning libraries sklearn and ngboost 
- Deep Learning library Tensorflow and Keras.


### Results



## Micro-Grids Project

Data Science tools to handle and prepare the data; Monte Carlo Method Optimization; Deep Reinforcement Learning;

### Project Info
Not ready yet
 
A conversational chatbot in [telegram](http://t.me/)  [nlp course by Higher School of Economics](https://www.coursera.org/learn/language-processing/home/welcome).

### Technologies Used
- Coded in python;
- Data-Science libraries such as pandas and numpy;
- Machine learning libraries sklearn;
- (...);



### Results


## Heating Fluid Selection

Data Science tools to handle and prepare the data; Linear Regression; Polinomial Regression;

### Project Info
Not ready yet
 
A conversational chatbot in [telegram](http://t.me/)  [nlp course by Higher School of Economics](https://www.coursera.org/learn/language-processing/home/welcome).

### Technologies Used
- Coded in python;
- Data-Science libraries such as pandas and numpy;
- Machine learning libraries sklearn;
- (...);



### Results


---

# Aeronautics Projects

Since I was a kid I allways felt fascinated by planes and really fast and precise cars like F1 cars. 

## Airfoil Performance and Range
Data exploration and analysis; Automation; Simulation;

### Project Info

[Wings Aerodynamics](https://github.com/perkier/CFD#wings-aerodynamics) is a Python Package to:
- Automate the mesh creation process in ICEM CFD;
- Prepare journal files automaticly to be ran in ANSYS FLUENT;
- Data visualization of the results (Lift and Drag);
- Simulate flight times and distances;

The most interesting part of this package is the Flight Simulator. With aerodynamics parameters (Lift and Drag Coefficient) simulated in ANSYS FLUENT the resulting data files where read through a custom made pipeline and then, using mathematical modeling and simulation I created a flight simulator which measures the distances traveled by an airfoil at Constant Speed or without acceleration - the parameters had to be allways updating because the drag depends on the velocity and the velocity must be decreasing since there is no engine power - with constant wing angle or variable angle. The most important flight parameters (e.g. Weight, Wing depth and others) are fully changable.



### Technologies Used

- Coded in python;
- Data-Science libraries such as pandas and numpy;
- Machine learning libraries sklearn;
- Meshes made in ICEM CFD with python automated scripts;
- CFD Simulations made in ANSYS FLUENT;


### Results

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


## CFD Result Analysis - Mesh Independance 
Data exploration and analysis; Data Visualisation;

### Project Info

The grid independence needs to be studied in order to minimize the impact of the grid size on discretization errors and computational cost. The grid size needs to be optimized to be small enough to guarantee that the results are independent of the mesh. The usual process is to increase 20-25% the mesh cells and compare the final flow results, defining an error-margin (normally 1-2%). However, there is no way to know where the difference is.

[Mesh Independance script](https://github.com/perkier/CFD/blob/master/Result_Analysis/Mesh_Independance_Analysis.py) compares a user-defined parameter (e.g. velocity) between the denser mesh and the original mesh. Finite Volumes techniques were used to approximate the denser mesh with the original one, as the coordinates of each cell varied between the meshes.

### Technologies Used

- Coded in python;
- Data-Science libraries such as pandas and numpy;
- Finite Volumes method;

### Results

![Gif of the Results](https://i.imgur.com/3T3feNc.gif)


---

# Marketing Projects

Maerketing is (...). 

## Twitter Sentiment Analysis
Data exploration and analysis; Deep Learning Classification; Natural Language Processing;

### Project Info

[Wings Aerodynamics](https://github.com/perkier/CFD#wings-aerodynamics).

### Technologies Used

- Coded in python;
- Data-Science libraries such as pandas and numpy;
- Deep Learning libraries Tensorflow;
- Natural Language Processesing Library NLTK;

### Results

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |



---

### Lets talk
I welcome feedback and suggestions! 

I’d love to hear from you about new ideas on how to implement innovative ideas. 

Contact me at diogoncsa@gmail.com or add me on [Linkedin](https://www.linkedin.com/in/diogoncsa/).
