基于深度强化学习的桥梁经济跨径选择

张乐业1，田翔翔1，张成利2，张洪俊3

（1. 江苏财会职业学院，连云港222061；
2. 连云港开放大学，连云港222006；
3. 万世先行数智交通科技有限公司，南京210016）

摘要：利用深度Q网络算法实现桥梁经济跨径的选择。桥梁跨径的选择对桥梁的总造价有显著影响，合理的跨径选择可以降低工程成本。对桥梁经济跨径进行理论分析，推导出经济跨径的理论求解公式。详细描述了桥梁模拟环境的构建过程，包括环境的观测空间、动作空间和回报函数等。构建智能体，利用卷积神经网络来逼近Q函数，采用贪婪策略进行动作选择，通过经验回放机制进行训练。测试验证了智能体能够成功学习到最优策略，实现桥梁经济跨径的选择。本研究为桥梁设计领域提供了一种潜在的决策工具。

关键词：强化学习；桥梁经济跨径；深度Q网络；桥梁模拟环境；智能体

本任务基于Python3.10编程语言、OpenAI Gym0.26.2强化学习工具包、TensorFlow2.10及Keras2.10深度学习平台框架。

Economic span selection of bridge based on deep reinforcement learning

Leye Zhang1，Xiangxiang Tian1，Chengli Zhang2，Hongjun Zhang3

（1. Jiangsu College of Finance & Accounting, Lianyungang, 222061, China;
2. Lianyungang Open University, Lianyungang, 222006, China;
3. Wanshi Antecedence Digital Intelligence Traffic Technology Co., Ltd, Nanjing, 210016, China）

Abstract：Deep Q-network algorithm is used to select economic span of bridge. Selection of bridge span has a significant impact on the total cost of bridge, and a reasonable selection of span can reduce engineering cost. Economic span of bridge is theoretically analyzed, and the theoretical solution formula of economic span is deduced. Construction process of bridge simulation environment is described in detail, including observation space, action space and reward function of the environment. Agent is constructed, convolutional neural network is used to approximate Q function,ε greedy policy is used for action selection, and experience replay is used for training. The test verifies that the agent can successfully learn optimal policy and realize economic span selection of bridge. This study provides a potential decision-making tool for bridge design.

Keywords: reinforcement learning; economic span of bridge; deep Q-network; bridge simulation environmen; agent

This task is based on Python 3.10 programming language, OpenAI Gym 0.26.2 reinforcement learning toolkit, TensorFlow 2.10 and Keras2.10 deep learning platform framework.
