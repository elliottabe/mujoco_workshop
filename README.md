# This is a GitHub Repo for the SOAR/BISCUIT 2024 workshop on MuJoCo by Elliott Abe. 

# [Introduction Slideshow](https://docs.google.com/presentation/d/1kLpJ7nwJPFg7W-CnRZL_Ey9YjGakV3mL9xBlP_S7TU0/edit?usp=sharing)

# Notebooks for workshop
- Introduction to MuJoCo
  - This [notebook](./Introduction01.ipynb) introduces the basics of MuJoCo models, simultation and rendering: &nbsp;  
  <a target="_blank" href="https://colab.research.google.com/github/elliottabe/mujoco_workshop2024/blob/main/Introduction01.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

- Flybody Example
  - The [flybody notebook](./Flybody_example.ipynb) covers the basics of working with the biomechanical model of the fruitfly created by Janelia: &nbsp;  
  <a target="_blank" href="https://colab.research.google.com/github/elliottabe/mujoco_workshop2024/blob/main/Flybody_example.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
</a>

- MuJoCo MJX 
    - MJX is the version of MuJoCo that runs [JAX](https://jax.readthedocs.io/en/latest/quickstart.html) in the backend and enables GPU simulations and environments: &nbsp;



# Local Installation Instructions

Clone the git repo from:  
`git clone https://github.com/elliottabe/mujoco_workshop2024.git`

Enter the mujoco_workshop2024 folder:  
`cd mujoco_workshop2024`

## Setup for installing conda environment and dependencies
To install the repo there is a conda environment that will install the necessary packages. Make sure you are in the pytorchGLM Github directory.  
Use command:  
`conda env create -f environment.yaml`

After installing activate the conda environment:  
`conda activate mujoco_workshop`

After installing the conda environment. Run this command to install pip reqruirements:  
`pip install -r requirements.txt`