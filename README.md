# Advanced Machine Learning Bonus Project
Bonus Assignment for the ML-lecture for WWI-DSA-18 at DHBW Mannheim

In this Repository I worked on Copycat CNN and Knockoff Nets via their respectiv Trusted-AI implementation in the Adversarial Robustness Toolbox.

In addition because those did not work properly I captured the idea of a copycat cnn in a simple transfer learning approch:
I took a trained classifier used by a fellow student and tried if I could perform simular performance by taking a pretrained VGG and using a not problem domain specific dataset (cifar100).

The PDF and the Assigment_9936663.ipynb make up the proposal for the assignment, the rest is further explained below:

[Assigment](https://github.com/FatManWalking/ml_bonus/blob/main/Assignement_9936663.ipynb) is to be considered the main proposal and contains the simple approch explained in the paper.

[Own_Knockoff](https://github.com/FatManWalking/ml_bonus/blob/main/Own_Knockoff.ipynb) is a failed approch, which took me much time and effort trying to solve conflicts between PyTorch, Tensorflow 1 and 2 and the used ART Framework. It helped me understand the topic but does as of today not properly work.

[Simple](https://github.com/FatManWalking/ml_bonus/blob/main/Simple_Demonstration.py) is a very simplfied version of Own_Knockoff and was just for me to understand the framework better.


Google Drive Links to Models and Data:

- [Bees and Ants](https://drive.google.com/drive/folders/1gUbGzQ5vPbUqa9toMNMOiCB5_XW-qa4E?usp=sharing)
- [Victim-Model](https://drive.google.com/file/d/1-N_JyEweW04Hp4AP89iRreywGkYGSOX8/view?usp=sharing)
- [Trained_Copycat VGG](https://drive.google.com/file/d/1cXp1h0aGMyFc1LXMDXZ8Hjq_PYGNXX4C/view?usp=sharing)
- [Trained Copycat Res](https://drive.google.com/file/d/1-3oySTgLph1iAioOMHC9elhzaruIyQ_8/view?usp=sharing)
- [Trained Victim VGG in the Failed Approch](https://drive.google.com/file/d/1mHaKVhgT6Uv3_dWzYETLF4wR3o4leXvA/view?usp=sharing)
