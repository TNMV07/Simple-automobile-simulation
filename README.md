# AI-Generated Autonomous Robot Simulation in MuJoCo

Welcome to the **Autonomous Robot Simulation** repository, developed by Tran Nam Minh Viet([https://www.linkedin.com/in/vi%E1%BB%87t-tr%E1%BA%A7n-11755a407/?skipRedirect=true]). 

This project demonstrates the power of Generative AI (LLMs like ChatGPT, Gemini, Claude) in rapid engineering and robotics prototyping. With just simple text prompts, we generated a functional, highly realistic physics simulation of an autonomous mobile robot navigating and avoiding obstacles.

## Key Features
* **AI-Driven Generation:** The core simulation logic and environment were primarily generated using Large Language Models, significantly reducing development time.
* **Realistic Physics:** Built on top of **MuJoCo** (Multi-Joint dynamics with Contact), ensuring highly accurate physical interactions and kinematics.
* **Obstacle Avoidance:** Features a dynamic environment where the mobile robot must navigate around randomly or explicitly placed obstacles (represented as red blocks).
* **Python Integration:** Seamlessly integrated with Python for easy logic modification, data collection, and algorithm testing.

## Tech Stack
* **Language:** Python 3.10+
* **Physics Engine:** MuJoCo (`mujoco` python package)
* **Computation:** NumPy (for matrix and physical calculations)

## Getting Started

### Prerequisites
Make sure you have Python installed on your system. You will also need to install the required dependencies:

```bash
pip install mujoco & numpy
To run the code you can use this to run in terminal or you can click the run button.
```bash
python test_mujoco.py
