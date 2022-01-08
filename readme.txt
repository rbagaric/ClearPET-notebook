
The folder contains the description of a ClearPET camera for the GATE simulation.

The camera is composed of a 20x4 crystal block as a ring. Each crystal block contain 8x8 crystal (2.0 mm). The phantom is a water cylinder. The source is in the cylinder, not centered (offset 5 and 7 cm).

To run the simulation, just type:

Gate mac/main.mac

The default macro considers a source of 2x10 kBq during 2x100 seconds. About 3.8 million particles are generated. The simulation took about 6 min of computation time. 

The analysis of output may be perform via the python notebook in the py/ folder. You need to install 'jupyter lab' (formerly know as 'jupyter notebook'): https://jupyter.org 
Once installed, type: 'jupyter lab' in the py/ folder and select the file pet.ipynb in the web interface. 


