## By Aser Atawya and Michele Tang
This project leverages the power of deep neural networks to design a model capable of simulating human driving in a virtual environment with the help of Udacity open-source self-driving car simulator.

# Building a Model
## Introduction
The development of deep neural network models has revolutionized the field of autonomous driving, providing a powerful tool for training autonomous cars to navigate and make decisions on the road. This project will leverage the power of deep neural networks to design a model capable of simulating human driving in a virtual environment with the help of open-source self-driving car simulators.

Developing a self-driving car is a complex process that requires automating an array of human functions, such as perception of surroundings, following traffic laws, and decision-making. A typical self-driving car would incorporate many machine learning models with each model performing different functions; for instance, the self-driving car needs a computer-vision model to identify traffic lights and road signs as well as a reinforcement-learning model to make decisions, such as whether the car will take a turn. Also, the development of self-driving cars extends beyond the machine learning algorithms to entail development of sensors, radars, and hardware components that can provide accurate inputs to the machine learning models.

We decided to use an open-source car simulator to focus only on the machine learning portion of the self-driving car development. And the most common form of machine learning algorithms used in autonomous cars is neural networks. Four of the most common deep learning methods used in the development of self-driving cars are convolutional neural networks, recurrent neural networks, auto-encoders, and deep reinforcement learning[^1]. The problems the models need to solve include obstacle detection, scene classification and understanding, lane recognition, path planning, motion control, and traffic signs and lights recognition[^1]. Previous research has put emphasis on safety by developing models capable of dealing with bad drivers of other cars, right of way laws, unstructured roads, pedestrians, and responsibility for actions[^2].



# References
[^1] J. Ni, Y. Chen, Y. Chen, J. Zhu, D. Ali, C. Weidong, “A Survey on Theories and Applications for Self-Driving Cars Based on Deep Learning Methods,” in Applied Sciences, vol. 10, no. 8, 2020. [https://doi.org/10.3390/app10082749](https://doi.org/10.3390/app10082749)

[^2] S. Shalev-Shwartz, S. Shammah, A. Shashua, “On a formal model of safe and scalable self-driving cars,” in ARXIV, Aug. 2017. https://arxiv.org/abs/1708.06374
