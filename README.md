# mujoco_resources

# Effy-M

**Team Members**

Rainer Gardner-Olesen,
Anna Le,
Effy Pelayo Tran

### Paper

**Title**

DeepMimic: Example-Guided Deep Reinforcement Learning of Physics-Based Character Skills


**Authors**

written by Xue Bin Peng, Pieter Abbeel, Sergey Levine, Michiel van de Panne (University of California, Berkeley, University of British Columbia)


**Link**

https://xbpeng.github.io/projects/DeepMimic/index.html



### Results

![Alt Text](comparison.gif)

### Presentation Slides
https://docs.google.com/presentation/d/1fNaSF0vc3GV75YXFUuxBOuI8nCAfdlioqXwulEFPVus/edit

### How to Run Code

1) Place make_him_walk folder into your google drive
2) Open code.ipynb
3) Run Installation Commands cell
4) Run Parse the Motion Capture into qpos & qvel cell
5) Pick one of the Define Humanoid Env cells to play (We recommend Define Humanoid Env for Walking in Circle, as that produced the results seen in the gif above.)
6) Run Train. We recommend setting the timestep hyperparemter to about 30_000_000 to 40_000_000 timesteps.
7) Run Save Trained Model cell to save trained model into Google Drive
8) In Render Trained Policy cell at the bottom, edit the render path to be the path you saved your train model to and play the cell
9) Wait a bit and a video should play of your trained guy
