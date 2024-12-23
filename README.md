# Celestial_Bodies
Simulation of $N$ Celestial Bodies Interacting under a gravitational potential. The code was written by Georgios Kementzidis, Patryk Kwoczak, Yuxuan Ye for the final project of the course "Scientific Programming in C++". In this implementation we emphasize the use of Object Oriented Programming.

You can run the scripts `simulateOrbit.cpp`, `simulateElliptic.cpp`, `simulateStars.cpp`, `simulateAsteroid.cpp`. You can also change the system content by editing the body definitions in the main() function.

So, first you run the cpp file:
`g++ -std=c++11 -o test simulateOrbit.cpp`

You run the executable:
`./test`

And then, you run the `plot_all_trajectories.py` python script:
`python3 plot_trajectory.py`

Within this python script, you can adjust the size of the objects included in the simulation by changing the scalar on lines 45-46. You may also edit the name of the saved file, as well as the path of the directory where you want to save the generated gif file. Also, you may want to edit the names of the csv files you are trying to load.