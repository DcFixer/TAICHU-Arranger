功能
=======
简介
-----
TC(TAICHU)-Arranger是基于kubebuilder编写的容器批量计算控制器，
用于分布式强化学习训练框架在集群上的任务部署。目前的分布式强化学习训练框架主要专注于算法的集成，
在计算资源尤其是多机资源的协调利用方面支持欠佳。
TC-Arranger为TCRL(TAICHU Reinforcement Learning Framework)在复杂任务训练场景上的应用提供支持，
为其提供CPU,GPU等资源的调度能力。

TCRL
-----

特性
----
支持多种pod调度策略，包括
 * Binpack policy
 * LeaderFirst policy
 * MinFragmen policy
 * JobAffinity Policy
 * JobAntiAffinity

支持多种Job调度策略，包括
 * PriorityPolicy
 * DRFPolicy