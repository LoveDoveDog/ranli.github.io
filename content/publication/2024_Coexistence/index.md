---
title: "Coexistence Between Task- and Data-Oriented Communications: A Whittle's Index Guided Multiagent Reinforcement Learning Approach"
date: 2024-01-01
publishDate: 2024-01-01
authors: ["Ran Li", "Chuan Huang", "Xiaoqi Qin", "Shengpei Jiang", "Nan Ma", "Shuguang Cui"]
publication_types: ["2"]
abstract: "We investigate the coexistence of task-oriented and data-oriented communications in an Internet of Things system that shares a group of channels, and study the scheduling problem to jointly optimize the weighted Age of Incorrect Information (AoII) and throughput, which are the performance metrics of the two types of communications, respectively. This problem is formulated as a Markov decision problem, which is difficult to solve due to the large discrete action space and the time-varying action constraints induced by the stochastic availability of channels. By exploiting the intrinsic properties of this problem and reformulating the reward function based on channel statistics, we first simplify the solution space, state space, and optimality criteria, and convert it to an equivalent Markov game, for which the large discrete action space issue is greatly relieved. Then, we propose Whittle’s index guided multiagent proximal policy optimization (WI-MAPPO) algorithm to solve the considered game, where the embedded Whittle’s index module further shrinks the action space, and the proposed offline training algorithm extends the training kernel of conventional multiagent proximal policy optimization to address the issue of time-varying constraints. Finally, numerical results validate that the proposed algorithm significantly outperforms state-of-the-art Age of Information (AoI)-based algorithms under scenarios with insufficient channel resources."
featured: false
publication: "*IEEE Internet of Things Journal*"
---
