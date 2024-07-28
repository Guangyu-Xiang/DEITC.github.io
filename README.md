# Demonstration-Environment-Infromed Task Chaining for SC-AIRL of Long-Horizon Tasks
In this work, we were interested in investigating the efficacy of SC-AIRL on long-horizon tasks. SC-AIRL is a form of Inverse Reinforcement Learning (IRL) that decomposes long-horizon tasks into multiple sub-tasks, where a discriminator, acting as a reward signal, and sub-policies are simultaneously learned using expert data. Empirically, we found that this state-of-the-art IRL-based method is unable to effectively solve longer-horizon manipulation tasks. We demonstrated that this is because SC-AIRL is susceptible to state shifts, where starting the next sub-task from an unsuitable state can lead to failure. Below, we show the connection process of SC-AIRL and a simplified and abstract example where this occurs：
