# Navigation
##### Project 1 - Training agent to collect bananas in unity environment with Deep Q-Learning

## 1. Environment

In this project I used a collect bananas unity environment adapted from the Unity ML-Agents toolkit. This envirionment was provided by Udacity.
An agent in action is presented below:

<p align="center">
  <img src="banana.gif" alt="drawing" width="700"/>
<p/>
<p align="center">
  Credits: Image taken from the content of Deep Reinforcement Learning Nanodegree - Udacity
<p/>

### 1.1 State Space

**According to information from Udacity:** The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.


### 1.2 Action Space

**According to information from Udacity:**  Given state information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:


- `0` - move forward.
- `1` - move backward.
- `2` - turn left.
- `3` - turn right.


### 1.3 Environment Rewards
**According to information from Udacity:** A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas. 

>> The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

---

## 2. Getting Started

Follow instruction to install dependencies to run the code on **Linux**

### Dependencies

To set up your python environment to run the code in this repository, follow the instructions below.

1. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.

```bash
git clone https://github.com/BrAM-breno/Navigation.git
cd Navigation
```

2. Create and activate a new environment from `environment.yml` file.

```bash
conda env create -f environment.yml
conda activate drlnd
```

3. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```


