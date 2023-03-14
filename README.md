# take_off_drone
 
Requirements and Installation

The repo was written using Python 3.8 with conda on  Ubuntu 20.04

On  Ubuntu
Major dependencies are gym, pybullet, stable-baselines3, and rllib

Video recording requires to have ffmpeg installed, On Ubuntu

$ sudo apt install ffmpeg


please install the following packages

python = "3.8"

numpy = ^1.22"

Pillow = "9.0"

matplotlib = "3.5"

cycler = "0.10"

gym = "0.21"

pybullet = "3.2"

torch = "1.11.0"

"ray[rllib]" = "1.9"

stable-baselines3 = "1.5.0"

scipy = "1.8"

tensorboard = "2.9"



learn.py  is an RL example to take-off using stable-baselines3's A2C or rllib's PPO

$ cd take_off_drones/drones/examples/

$ python3 learn.py           
