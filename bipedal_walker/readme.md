## What is this project?
This project is our solution to BipedalWalker-v2 environment. Our model is based on Deep Q Learning (DQN) model.

## What actually is BipedalWalker-v2 environment?
BipedalWalker-v2 is one of [OpenAI Gym](https://gym.openai.com/envs/) environments. 
You may find it under [Box2D](https://gym.openai.com/envs/#box2d) environments.
The goal of this environment is to create a model of 2D robot that learns how to walk. 
More details about BipedalWalker-v2 environment can be found [here](https://github.com/openai/gym/wiki/BipedalWalker-v2).

## What are the dependecies for this project?
* Python 3.5
* PyTorch 
* OpenAI Gym
* Box2D

 ## How to setup BipedalWalker-v2 environment?
* install PyTorch

    * using pip:</br>

	      pip3 install http://download.pytorch.org/whl/cu80/torch-0.3.0.post4-cp35-cp35m-linux_x86_64.whl
	      pip3 install torchvision
   
    * using conda:</br>

	      conda install pytorch torchvision -c pytorch
   
* install OpenAI Gym

	  pip install gym
   
* install Box2D(with conda)

	  conda install -c https://conda.anaconda.org/kne pybox2d

 ## A demo showing current state of project
![Alt Text](https://github.com/piojanu/GradientAILab/blob/master/bipedal_walker/assets/bipedal_walkergif.gif)
