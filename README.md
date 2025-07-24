# This is a GitHub Repo for the workshop on MuJoCo by Elliott Abe. 

This workshop was designed to be able to work fully in collab notebooks with internet access. If you would like to install on your local computer, see install instructions at the bottom. 

# [Introduction Slideshow](https://docs.google.com/presentation/d/1db3w0XCbqaA_4OCZj-JK-Y6mf74p1sOYVRD3Rk6ZzEQ/edit?usp=sharing)

# Notebooks for workshop
- Introduction to MuJoCo
  - This [notebook](./Introduction.ipynb) introduces the basics of MuJoCo models, simulation, and rendering: &nbsp;  
  <a target="_blank" href="https://colab.research.google.com/github/elliottabe/mujoco_workshop2024/blob/main/Introduction.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

- Model Editing with MjSpec
  - This [notebook](./mjspec.ipynb) introduces the basics of how to programatically edit and manipulate models in MuJoCo. &nbsp;  
    <a target="_blank" href="https://colab.research.google.com/github/elliottabe/mujoco_workshop2024/blob/main/mjspec.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

- Flybody Example
  - The [flybody notebook](./Flybody_example.ipynb) covers the basics of working with the biomechanical model of the fruitfly created by Janelia: &nbsp;  
  <a target="_blank" href="https://colab.research.google.com/github/elliottabe/mujoco_workshop2024/blob/main/Flybody_example.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  </a>

- MuJoCo MJX 
    - MJX is the version of MuJoCo that runs [JAX](https://jax.readthedocs.io/en/latest/quickstart.html) in the backend and enables GPU simulations and environments: &nbsp;  
    <a href="https://colab.research.google.com//github/elliottabe/mujoco_workshop2024/blob/main/MJX_Examples.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt= "Open In Colab" /></a>


# Additional notebooks to explore: 
- DM_control tutorial (DM_Control will eventually be deprecated): 
  -  <a href="https://colab.research.google.com/github/google-deepmind/dm_control/blob/main/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt= "Open In Colab" /></a>

- The **LQR** tutorial synthesizes a linear-quadratic controller, balancing a humanoid on one leg:
  -  <a href="https://colab.research.google.com/github/google-deepmind/mujoco/blob/main/python/LQR.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt= "Open In Colab" /></a>

- The **least-squares** tutorial explains how to use the Python-based nonlinear least-squares solver:
  -  <a href="https://colab.research.google.com/github/google-deepmind/mujoco/blob/main/python/least_squares.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt= "Open In Colab" /></a>

- The **differentiable physics** tutorial trains locomotion policies with analytical gradients automatically derived from MuJoCo's physics step:
  -  <a href="https://colab.research.google.com/github/google-deepmind/mujoco/blob/main/mjx/training_apg.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt= "Open In Colab" /></a>


# Local Installation Instructions

Clone the git repo from:  
`git clone https://github.com/elliottabe/mujoco_workshop.git`

Enter the mujoco_workshop folder:  
`cd mujoco_workshop`

## Setup for installing conda environment and dependencies
To install the repo there is a conda environment that will install the necessary packages. Make sure you are in the mujoco_workshop Github directory.  
Use command:  
`conda env create -f environment.yaml`

After installing activate the conda environment:  
`conda activate mujoco_workshop`

After installing the conda environment. Run this command to install pip reqruirements:  
`pip install -r requirements.txt`
