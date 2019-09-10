# ai_research
This repository is to learn about all of the current reinforcement learning algorithms. 

The first step according to Open AI is to start implementing algorithsm.  This is the list to be implemented. 

 - [] VPG(Reinforce): Vanilla Policy Gradient
 - [ ] DQN
 - [ ] AC2
 - [ ] PPO
 - [ ] DDPG
 - [ ] one of these parallelized

You should probably start with vanilla policy gradient (also called REINFORCE), DQN, A2C (the synchronous version of A3C), PPO (the variant with the clipped objective), and DDPG, approximately in that order. The simplest versions of all of these can be written in just a few hundred lines of code (ballpark 250-300), and some of them even less (for example, a no-frills version of VPG can be written in about 80 lines). Write single-threaded code before you try writing parallelized versions of these algorithms. (Do try to parallelize at least one.)

