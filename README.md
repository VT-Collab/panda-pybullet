# Panda Environment

Simple PyBullet Environments for the Panda Robot Arm. Developed for the [Collab](https://collab.me.vt.edu/).

## Quickstart

Use these commands to quickly get set up with this repository, and start up the Panda Arm Environments.

```bash
# Clone the Repository
git clone https://github.com/VT-Collab/panda-pybullet.git
cd panda-pybullet

# Create a Conda Environment using `environment.yml`
conda env create -f environment.yml
```

## Start-Up (from Scratch)

Use these commands if the above quick-start instructions don't work for you, or you prefer to maintain your own Python
packaging solution, and want to make sure the dependencies are in check. If you're just trying to use the code, look at 
the Quickstart section above.

```bash
# Create & Activate Conda Environment
conda create --name panda-env python=3.7
conda activate panda-pybullet

# Install Dependencies 
pip install pybullet numpy
```

## How to Run

This repo includes three sample environments, as well as the utility functions for assests (i.e., objects to interact with) and teleoperation (i.e., script for a joystick). The teleoperation environment (env_3) will not work run unless a joystick is attached!

To see all three sample environments, run:
```bash
python3 main.py
```
