# Introduction
This is my implementation of the second project in the Udacity Deep Reinforcement Learning Nanodegree. Below, I will describe some information about this project.
# Project Details
The project involved working in a Unity environment where the agent had to move a double-jointed arm to a target location. A reward of 0.1 is provided for each movement in the right location. Here are the values for the state and action spaces:
* State space: 33 dimensions (velocity, perception of objects in front of the agent, etc.)
* Action space: continuous (4 numbers between -1 and 1, referring to the torques applied)

The environment is considered solved when the agent has achieved an average reward of +30 over 100 episodes.
# Running the Code
If you want to run the code, clone/download this repo to your computer, and download the environment (<a href='https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip'>32-bit Windows</a>, <a href='https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip'>64-bit Windows</a>, <a href='https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip'>Mac</a>, <a href='https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip'>Linux</a>). Then, open `ContinuousControl.ipynb`. Make sure you set the proper path to your environment in the cell with this code: 
<pre><code>env = UnityEnvironment(file_name="PATH_TO_ENVIRONMENT")</code></pre>
Then, run all code cells in the notebook, while making sure to avoid running the `env.close()` cell until after the model has been trained.
