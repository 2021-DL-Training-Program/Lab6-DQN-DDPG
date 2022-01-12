# Lab6-DQN-DDPG
This repository is about the implementation of DQN and DDPG.
## Package you need
Before coding, you may need to install some packages.
```
pip3 install gym
```
```
pip3 install box2d
```
## Training and Testing
For training, you can run the commands below.
```
python3 dqn.py
```
```
python3 ddpg.py
```
If you only want to test your model, run these commands.
```
python3 dqn.py --test_only
```
```
python3 ddpg.py --test_only
```
## Update(2022/1/12)
We have added tensorboard and rendering functions.<br><br>
For tensorboard, you can click "Launch Tensorboard Session" to check the change of your rewards during training.
![image](https://user-images.githubusercontent.com/68993019/149170835-72e84c5e-5173-48ce-b40c-882b657e4527.png)
<br><br>It should look like the following picture:<br>
![image](https://user-images.githubusercontent.com/68993019/149171918-68b64655-3765-4d96-b834-37a43d028e8a.png)
<br><br>For rendering, you can run the commands below:
```
python3 dqn.py --render
```
```
python3 ddpg.py --render
```
<br>By default, the game will be rendered during testing. If you want to render the episodes during training, you can modify the code by yourselves(same way as testing).
<br><br>Please make sure that you have an GUI interface before rendering.



