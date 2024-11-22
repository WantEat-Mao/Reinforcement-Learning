paper：Deep Reinforcement Learning-Based Task Scheduling in IoT Edge Computing

# GitHub Repository
This is a GitHub repository for reinforcement learning algorithms for task scheduling in edge-cloud computing.
To solve a task-offloading problem, different problem-solving techniques such as mathematical programming, machine learning, heuristics, meta-heuristics, and game theory can be applied.
Reinforcement learning algorithms can be used to learn effective scheduling policies to meet specific performance objectives while satisfying problem constraints.
This work focuses on deadline-constrained task offloading in the edge-cloud and proposes a reinforcement learning algorithm for the problem.
Considering a set of independent tasks, the objective is to maximize the number of tasks that meet their deadlines and minimize the deadline violation time of the tasks that cannot meet their deadlines.
In this work we use Q-learning algorithms, the central idea behind Q-learning is to learn a Q-table, denoted as ¨Q(s,a)¨. This table represents the expected cumulative reward of taking action ¨a¨ in state ¨s¨. Before learning begins, the Q-values are initialized to a fixed value, e.g. 0. Then, in each step, the agent selects an action ¨a¨ in state s, receives a reward, and the system transfers to a new state ¨s'¨, and the Q-value is updated based on the received rewards and the estimated future rewards. The goal of a Q-learning algorithm is to learn the optimal policy and follow it thereafter.
