# Open Resource via Mujoco & Related Engines  <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a>

This repository collects a series of projects built upon MuJoCo and similar engines, such as Mjx, Genesis, and the upcoming Newton. The scope includes, but is not limited to, physics simulation, modeling, control, and training. Currently, the projects are broadly categorized into three domains: Robotics (my personal area of focus), Physics Simulation & Computation, and Biomedical Applications. As my own exposure to many of these projects is limited and this repository was created out of personal interest, pull requests are highly welcome to help us improve this collection together. A dedicated webpage will be launched in the future based on the completeness and volume of the content.
    
I hope this warehouse can become more complete. If you have relevant content collection in different fields, feel free to  **feel free to [*open issues*](https://github.com/Roundly/Mujoco-Open-Resource/issues/new) or [*pull requests*](https://github.com/Roundly/Mujoco-Open-Resource/compare)**. Contributions in any form to make this list more comprehensive are welcome.

If you find this warehouse very helpful, please *star!🌟*

> Generally speaking, there are many open-source projects related to Isaac Gym. I created this repository with the hope of finding sufficiently unique or complete project resources in the subfield of MuJoCo and related engines. Therefore, please make sure to filter and add only the relevant ones! Of course, we also welcome the use of sim2sim technology to achieve the transition from Isaac Gym to MuJoCo, but please specify the exact folder and the category of the technical implementation!
<br>请提供与Mujoco高度相关的开源项目，包括从issac gym通过sim2sim实现的mujoco也是可以的！


## 1. Official Documentation & Tutorials

- Mujoco  [[website](https://mujoco.org/)] [[github](https://github.com/google-deepmind/mujoco)]
- MuJoCo XLA (MJX)  [[document](https://mujoco.readthedocs.io/en/stable/mjx.html)] [[github](https://github.com/google-deepmind/mujoco/tree/main/mjx)]
- MuJoCo Playground [[website](https://playground.mujoco.org/)] [[github](https://github.com/google-deepmind/mujoco_playground)] [[Technical Report](https://playground.mujoco.org/assets/playground_technical_report.pdf)]

> For RL or mujoco, There are some open python library like Stable-Baselines3[[document](https://stable-baselines3.readthedocs.io/en/master/)] or Gymnasium[[document](https://gymnasium.org.cn/)], If you are not familiar with RL, You can search for them!

- Genesis [[website](https://genesis-embodied-ai.github.io/)] [[github](https://github.com/Genesis-Embodied-AI/Genesis)]

A highly recommended tutorial with video guides for mastering the basics of MuJoCo and Reinforcement Learning from my friend (XD).

- mujoco_learning repository [[github](https://github.com/Albusgive/mujoco_learning)] [[bilibili video](https://www.bilibili.com/video/BV1wMdHYVEnx?spm_id_from=333.788.videopod.sections&vd_source=7f728b80e21aaffa0f2781c650cbe2ce)]

## 2. Robotics

### 2.1 Trending(over 800 stars)

|  Initialism  |                        Artical / Name                        |     Type      | Base  |                             URL                              | Note(Optional)                                               |
| :----------: | :----------------------------------------------------------: | :-----------: | :---: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| NeurIPS 2023 | LocoMuJoCo: A Comprehensive Imitation Learning Benchmark for Locomotion |      IL       |  ALL  | [[Paper](https://arxiv.org/pdf/2311.02496)] [[github](https://github.com/robfiras/loco-mujoco)] |                                                              |
|      -       |                       Mujoco Menagerie                       |     Model     |  ALL  | [[github](https://github.com/google-deepmind/mujoco_menagerie)] | A collection of high-quality models for the mujoco physics engine. |
|   RSS 2023   |            ACT: Action Chunking with Transformers            | IL, Algorithm | ALOHA | [[paper](https://arxiv.org/abs/2304.13705)] [[github](https://github.com/tonyzhaozh/aloha)] |                                                              |
|              |                                                              |               |       |                                                              |                                                              |
|              |                                                              |               |       |                                                              |                                                              |

### 2.2 Others

| Classification / Engine | Repository name/Article | Type |     Base     |                             URL                              | Note(Optional) |
| :---------------------: | :---------------------: | :--: | :----------: | :----------------------------------------------------------: | -------------- |
|     Genesis/Mujoco      |  wheel_legged_genesis   |  RL  | Wheel-legged | [[github](https://github.com/Albusgive/wheel_legged_genesis)] |                |
|         Mujoco          |      MuJoCo_RL_UR5      |  RL  | Manipulator  |  [[github](https://github.com/PaulDanielML/MuJoCo_RL_UR5)]   |          UR5       |
|         Mujoco          |      MuJoCo-Dual-Arm    |  RL  | Manipulator  |  [[github](https://github.com/Autrio/MuJoCo-Dual-Arm)]       |   Franka Panda    |
| Mujoco | pointfoot-mujoco-sim | RL | Wheel-legged/Point foot | [[github](https://github.com/limxdynamics/pointfoot-mujoco-sim)] | 逐际动力开源 |
|                         |                         |      |              |                                                              |                |


## 3. Computational Physics

| Classification / Engine | Repository name/Article | Type | Base | URL  | Note(Optional) |
| :---------------------: | :---------------------: | :--: | :--: | :--: | -------------- |
|                         |                         |      |      |      |                |
|                         |                         |      |      |      |                |
|                         |                         |      |      |      |                |
|                         |                         |      |      |      |                |
|                         |                         |      |      |      |                |

## 

### 4.1 Biotechnology

| Initialism | Artical  |    Type    |             Base             |                             URL                              | Note(Optional) |
| :--------: | :------: | :--------: | :--------------------------: | :----------------------------------------------------------: | -------------- |
|  L4DC2022  | MyoSuite | Collection | Musculoskeletal Environments | [[github](https://github.com/MyoHub/myosuite)] [[paper](https://arxiv.org/abs/2205.13600)]  [[document](https://myosuite.readthedocs.io/)] |                |
|            |          |            |                              |                                                              |                |
|            |          |            |                              |                                                              |                |
|            |          |            |                              |                                                              |                |
|            |          |            |                              |                                                              |                |

### 4.2 Life Sciences

| Initialism  |                        Artical                        |    Type    |   Base    |                             URL                              | Note(Optional)     |
| :---------: | :---------------------------------------------------: | :--------: | :-------: | :----------------------------------------------------------: | ------------------ |
| Nature 2025 | Whole-body physics simulation of fruit fly locomotion | locomotion | Fruit fly | [[Paper](https://www.nature.com/articles/s41586-025-09029-4.pdf)] [[github](https://github.com/TuragaLab/flybody?tab=readme-ov-file)] | nature果蝇恐怖如斯 |
|             |                                                       |            |           |                                                              |                    |
|             |                                                       |            |           |                                                              |                    |




## LICENSE


    Open Resource via Mujoco & Related Engines ©2025 by Sheng Yanggang is licensed under CC BY-NC-SA 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/
