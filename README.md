# Data Drift and Model Adaptation in Industrial Settings
This repo contains the paper list and figures for [A Survey of Data Drift and Model Adaptation in Industrial Settings]().

## Abstract

总体框架~~~

<img src="images/framework%20v4.png" style="zoom: 33%;" />

## Scope and rationales

The scope of this survey is mainly defined by following aspects.

- 
- xx

## Citation

```
@article{chen2024a,
    title = {A Survey of Data Drift and Model Adaptation in Industrial Settings},
    author = {Chen, Jiao and Liu, Qianmiao and Dai, Suyan and He, Jiayi
    and Lv, Zuohong},
    journal={arXiv preprint arXiv:240x.xxxxx},
    year = {2024}
}
```

## Table of Contents

- [Industrial Applications](#Industrial-Applications)
  - Industrial Fault Diagnosis
  - Remaining Life Prediction
  - Laser Micro/Nano Processing
  - Planing and Control for Autonomous Driving
  - Biomorphic Robotic Motion Control
  - Additive Manufacturing Process Monitoring and Control
  - Gesture Recognition Based on Hydrogel Electronic Skin 
- [Definition of data drift](#Definition-of-data-drift)
- [Short-term Drift Adaptation Strategies](#Short-term Drift Adaptation Strategies)
  - Before Deployment
  - After Deployment
- [Long-term Drift Adaptation Strategies](#Long-term Drift Adaptation Strategies)
  - Continual/Lifelong Learning
  - Learn from Model

- [Challenges and Directions](#Challenge-and-Directions)
  - Framework/Platform Development
  - Datasets/Benchmarks
  - Integration with Large Models
  - Multi-Model Management
  - Knowledge Base Construction

## Industrial Applications
###  Industrial Fault Diagnosis

（工业故障诊断）

### Remaining Life Prediction

（剩余寿命预测）

### Laser Micro/Nano Processing

（激光微纳加工)

### Planing and Control for Autonomous Driving

（自动驾驶规划与控制，e.g., 自动清扫车）

### Biomorphic Robotic Motion Control

（仿生机器人运动控制）

### Additive Manufacturing Process Monitoring and Control

（增材制造过程监控及控制）

###  Gesture Recognition Based on Hydrogel Electronic Skin 

（水凝胶电子皮肤应用、e.g., 手势识别）

## Definition of data drift
The goal is to present a simple and intuitive overview of the definition, types, and case studies of data drift. Introducing related concepts: Out-Of-Distribution (OOD), Long-Tail Distribution, Non-IID, and Few-Shot Learning.

TODO： 给出一个示意图，代表不同的检测方法在cifar10数据集的检测效果。

## Short-term Drift Adaptation Strategies
### Before Deployment

Concept Drift Adaptation by exploiting Drift Type.*[ACM Transactions on Knowledge Discovery from Data 2023]*[[paper]([Concept Drift Adaptation by Exploiting Drift Type | ACM Transactions on Knowledge Discovery from Data](https://dl.acm.org/doi/abs/10.1145/3638777))]

#### Transfer Learning

#### Domain Adaptation

#### Federated Learning

Flower: A friendly federated learning research framework. *[arXiv'20]* [[Paper]](https://arxiv.org/pdf/2007.14390) [[Code]](https://github.com/adap/flower)

Fedml: A research library and benchmark for federated machine learning. *[arXiv'20]* [[Paper]](https://arxiv.org/pdf/2007.13518) [[Code]](https://github.com/FedML-AI/FedML)

#### Knowledge Distillation

### After Deployment

[Serving on Edge]

#### Parameter-Efficient

e.g., Prompt Adapter, LoRA, Prefix tuning

#### Resource-Efficient

e.g., Edge-Cloud Collaboration (by Chen), Test-Time Adaptation, Transfer Learning

EdgeFM: Leveraging Foundation Model for Open-set Learning on the Edge. *[SenSys'23]* [[Paper]](https://yanzhenyu.com/assets/pdf/EdgeFM-SenSys23.pdf)

#### Data-Efficient

e.g., Data Selection Mechanisms Based on Gradients, Entropy, Data Annotation (Language Models, Pseudo-Label Generation)

#### Test Time Adaptation

#### Gradual Domain Adaptation

[Serving on Cloud]

#### Edge Cloud Collaboration

Towards Edge-Cloud Collaborative Machine Learning: A Quality-aware Task Partition Framework.[[paper]](https://dl.acm.org/doi/abs/10.1145/3511808.3557080)

ECLM: Efficient Edge-Cloud Collaborative Learning with Continuous Environment Adaptation.[[paper]](https://arxiv.org/abs/2311.11083)

# Long-term Drift Adaptation Strategies

### Continual/Lifelong Learning

Memory efficient continual learning with transformers. *[NeurIPS'22]* [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2022/file/4522de4178bddb36b49aa26efad537cf-Paper-Conference.pdf)

#### Regularization Techniques for Model Adaptation

#### Parameter Isolation

#### Replay Methods

#### Analytic Learning

### Learn from Model

#### Model reuse

#### Meta learning

## Challenges and Directions
### Framework/Platform Development
### Datasets/Benchmarks
### Integration with Large Models
### Multi-Model Management
### Knowledge Base Construction