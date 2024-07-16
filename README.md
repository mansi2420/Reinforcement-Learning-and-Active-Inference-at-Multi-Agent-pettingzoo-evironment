# Reinforcement-Learning-and-Active-Inference-at-Multi-Agent-pettingzoo-evironment
The code for this project is provided named as:

RL_and_active_inference_mpe.ipynb

Different environment simulations are provided in folder “\environment_behaviour” as:
random_behavior.gif: This gif file shows how the agent behaves randomly in the
environment, it is available at:

https://pettingzoo.farama.org/environments/mpe/simple_spread/

simple_spread_a2c_5 (high exp).gif and simple_spread_a2c_6 (high exp).gif : These gif
files show how the agents perform with high exploration rate.

simple_spread_a2c_7(not deterministic).gif : This gif file shows how the agents perform
when they’re exhibiting stochastic behaviour instead of deterministic behaviour.

Rest of .gif files are some visual examples of how agents perform using the final RL model
trained.

Training logs are provided in the folder “\Logs”. These logs show all the training logs
obtained using tensorboard. To access these logs, user can refer to appendix, as well as run
the tensorboard command in cmd as: tensorboard –logdir Logs

The folder “\models” contains all the models trained when creating the RL model for our
environment. The final model used is: “simple_spread_v3_20230803-150705”.
