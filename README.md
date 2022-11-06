# Applying of Reinforcement Learning for Self-Driving Cars
Presentation : https://docs.google.com/presentation/d/10UAJBjj2w473teJY-cLwJKwF3cAmobX-QoBa_NMHl74/edit?usp=sharing

Stimulated self-driving cars under the policy of Proximal Policy Optimization by using the CarRacing environment.

# Car Racing v1 Update 

This repository for Deep reinforcement learning subject.

gym Car_Racing v1 env custom from [notanymike](https://notanymike.github.io/Solving-CarRacing/) 
for work with gym-0.23.1 and stable_baselines3

# Installation on Google colab
You can use is google colab LINK for [COLAB](https://colab.research.google.com/drive/193R2L_HAXHYIE5zsI-aydd31EeeenDTZ?usp=sharing)
1. Delete original gym on  `/usr/local/lib/python3.7/dist-packages/gym`
2. clone this repo on `/usr/local/lib/python3.7/dist-packages` normaly use 
    `cd /usr/local/lib/python3.7/dist-packages/` AND  `!git clone https://github.com/nutapol97/Deep_RL_Projec_Car_Racing.git`
3. install necessary lib by command   ``` !pip install stable-baselines3[extra] pyvirtualdisplay  pyglet==v1.3.2 gym[box2d]
!apt-get install python-opengl -y``` AND
`!apt-get install x11-utils > /dev/null 2>&1 
!pip install pyglet > /dev/null 2>&1 
!apt-get install -y xvfb python-opengl > /dev/null 2>&1` the last one is `!pip install gym pyvirtualdisplay > /dev/null 2>&1`





