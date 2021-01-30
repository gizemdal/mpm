# Material Point Method Jello Simulation with Taichi

<a name="description"/> 

## Project Description

This is the final project for Physically Based Animation (CIS-563), where I used the 2D Taichi MPM sample code provided by Dr. Jiang as a basis to implement a 3D MPM simulation of
elastic material.

You can check out the report included in this repository to learn more about the code structure and the MPM algorithm.

<a name="overview"/>

## Setup Overview

The MPM simulation for this assignment is coded in Taichi/Python3.8 on the Windows 10 platform. In order to install Taichi I followed the instructions on the Taichi website. When I was setting it up on my environment, I had to additionally install Python3.8 and the pip installer that was recommended on the console to make the Taichi code compile and run. If you don’t have it already, you must also have the numpy library installed before you can run this program. I additionally installed Houdini Apprentice on Windows to import the OBJ sequences of MPM particles and create a rendered demo, although this is not necessary to run the Taichi program itself. Without this 3D render, you should still be able to see a 2D visualization of the 3D simulation on the popup GUI window once you run the program. When you’re ready to run the code, simply cd into the same directory where the two-cubes.py file exists and then run the python two-cubes.py command from Visual Studio Code (or the Git Bash terminal if you do not have VSC).

<a name="results"/>

## Results

I have created two scenes with elastic materials where one scene is made of two cubes (two-cubes.py) and the other scene reads particle positions from an OBJ file to create two elastic bunnies (bunny.py). I used Houdini to sample a point cloud within the bunny geometry volume and exported it as an OBJ file (bunny_point.obj).

You can learn more about the results by checking out the report included in this repository.