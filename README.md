# Project Proposal - Applied Deep Learning

Student-Name: Paul Erpenstein
<br>
Student-ID: 12107369

## Project Summary

In recent years the demand for fast and easy package delivery has increased dramatically. The use of online retailers has become part of many peoples consumption habits. Automated package delivery would therefore be an interesting opportunity to save costs and increase the amount of packages that can be delivered. There have been previous attempts of using Deep Reinforcement Learning (DRL) to automate this and similar tasks by using unmanned aerial vehicles (UAV) to deliver said packages [1][2]. Muñoz et al. used a sophisticated 3D simulation to accomplish the training of the agents. They also employed different DRL methods [1]. The review of Azar et al. shows research that even goes as far as to train fleets of UAVs to act in complex aerial maneuvers [2].

In my project I will atempt to do the following:

* Create a simulation environment that models automated package delivery via UAVs
* Use DRL methods to train an agent to navigate a UAV in the simulated environment and deliver packages
* Create an interactive demo that allows users to place packages in the environment and see the agent taking care of its delivery

I will use the [Unity Game Engine](https://unity.com/) as well as the the [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents) to acomplish this task.

The project's execution will follow the following steps:

1. Set up a running project suite that combines the right versions of the used 3D- and ML-frameworks (4h)
2. Create the simulation environment
    * Create simple but readable 3D-assets (UAV, Package, Obstacles, Package pickup/delivery zone) (3h)
    * Create logical Unity components that express the semantics of the task (i.e. UAV controls, package pickup/dropoff logic) (5h)
    * Compose a 3D scene that combines the assets to represent a training scenario (3h)
3. Set up and run the DRL
    * Write python code that accesses the UAVs actions and define goals (6h)
    * Run the DRL (try different models, tweaks parameters and the environment, etc.) (8h)
4. Create an interactive Demo
    * Create camera controls for the user (2h)
    * Create interactive components (ability to place packages in pickup zones) (5h)
5. Preparing the submission
    * Writing a report (4h)
    * Creating a presentation (2h)

The above steps will most-likely not be executed in a sequantial manner, but in an iterative way. I will start of creating a minimum viable product. More complex aspect of the simulation like complex aerodynamics, UAV battery simulation or a dynamic environment will not be part of my initial ambitions. If I end up outperforming my time estimate I would however be very interested in implementing such features.

Total inital time estimate: 42h. This time estimate is obviously still optimistic and I am certain that I will encounter plenty of blockers and pitfalls during the project. This makes me quite certain I will need the buffer time to solve these issues. I am however very optimistic about completing the project in the given timeframe.

I would say that my project best falls into the "bring your own data" category. Since DRL projects don't really have any data this might seem unintuitive, but I think of the project as a "bring your own learnign setup" type of project. This I would argue is very close to the aforementioned project type. 

## Literature

[1] G. Muñoz, C. Barrado, E. Çetin, and E. Salami, “Deep Reinforcement Learning for Drone Delivery,” Drones, vol. 3, no. 3, 2019, doi: 10.3390/drones3030072.

[2] A. Azar et al., “Drone Deep Reinforcement Learning: A Review,” Electronics, vol. 10, Apr. 2021, doi: 10.3390/electronics10090999.
