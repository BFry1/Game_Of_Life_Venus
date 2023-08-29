# Venus_Game_of_Life
This repository contains the work carried out on the Venus Game of Life simulation, a MSc project investigating the feasibility of life in the clouds of Venus. The files in this repository are the simulations and code produced as part of the project.

The simulations are contained within the folders. The simulations were created in triples with three speeds available for viewing, fast, medium and slow. The folders also contain all of the .png files which were used in the creation of the .gifs.

The Game of Life code file can be opened on GitHub, then it is recommended to use the 'Open in Colab' button on the Preview pane to view this on Colab. Alternatively, the url for the code can be copiedand pasted into the the GitHub section of the pop-up box on Google Colab. All of the code has been written using the Python coding language.

The code is broken up into several sections as follows:
- The Imports
  - These are all of the necessary import to run the code

- The Function definitions
  - This code cell defines all of the functions used to create the Game of Life.
  - The function for plotting the simulation has several lines commented out, these can be included if the user wishes to view the simulation from additional angles.

- The Rules and Conditions for the Simulation
  - This cell contains all of the user defined starting conditions for the simulation.
  - Features which can be altered include: the living cell size, the initial configuration of cells, the rules for the Game of Life, the droplet (both 1 and 2) positions, sizes and velocities, the number of generations for the code to simulate, the zoom of the simulation and the transparency of the droplet. Defaults have been included as comments.
  - The folder number variable is where the files will be saved when running the simulation.

- A Droplet Surface Area and Volume Calculator
  - This cell calculates the surface area, the volume and the eccentricity of each of the individual droplets simulated and the total volume and radius corresponding to the total volume should the droplets merge.
  - This cell is only useful when investigating the effects of droplet parameters on the life.

- Model Generation 0
  - This cell displays the initial configuration of the living cells and the position of the droplets.
  - This cell is primarily used when altering the values in the 'Rules and Conditions for the Simulation' cell, to ensure the positions and sizes are as the user desires.

- Making the .png files
  - This cell is the main cell of the simulation which runs the Game of Life over the given number of generations.
  - There are lines commented out which simulate the merger and split of droplets and these can be included if the user wishes. If these are included, ensure the droplet velocities are such that they will collide.

- Making the .gif files
  - This cell takes the .png files and combines them in a stop-animation style animation to produce the animated simulation from this project.

- Displaying the .gif files
  - The .gifs can be displayed without needing to download them or open another window using this cell

- Downloading the .png and .gif files
  - This cell creates a zip folder in the local file directory on Google Colab containing all of the .png and .gif files created from the last time each of the cells were run.
  - To retain this folder on a personal drive, hover of the zip folder with the mouse cursor, click on the three dots, then click download and the folder will be downloaded to the downloads folder on the computer.

- Deleting unwanted files
  - This cell deletes any .png or .gif files and any .zip folders created, with the corresponding folder number variable.
 
- Practicality of Simulation
  - This cell provides some background data on the number density, pressure and temperature against altitude for the clouds of Venus.
  - The graphs created show how these variables are related to altitude and also include the middle cloud layer (the grey shaded region), showing how the droplets in this altitude band will experience temperature and pressure similar to that on Earth.
