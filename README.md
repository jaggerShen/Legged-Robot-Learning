# 以下内容随进度安排会不断更新
# 1 四足机器人开源平台
## 1.1 Stanford开源四足机器人
总地址：https://stanfordstudentrobotics.org/doggo  
8DOF-并联四足Doggo：https://github.com/Nate711/StanfordDoggoProject  
12DOF-串联四足Pupper（更推荐MIT cheetah）：https://pupper.readthedocs.io/en/latest/  

## 1.2 MIT cheetah开源四足机器人
实验室地址：https://biomimetics.mit.edu/  
对MIT开源机械结构的分析（12-DOF）：https://zhuanlan.zhihu.com/p/58077049  

## 1.3 国内比较好的开源入门学习平台——灯哥开源
B站：https://space.bilibili.com/493192058/  
Github：https://github.com/ToanTech/py-apple-structure  

## 1.4 国内比较好的四足机器人进阶学习——华北舵狗王
合集：https://zhuanlan.zhihu.com/p/69776564  

# 2 著名四足机器人介绍
## 2.1 以传统控制为主的波士顿动力 Spot
2019以前所发的专利解读：
https://zhuanlan.zhihu.com/p/62941774
https://zhuanlan.zhihu.com/p/66293702

## 2.2 以强化学习为主增强环境适应能力的苏黎世联邦理工 ANYmal
论文：
《Learning agile and dynamic motor skills for legged robots》-2019
《Learning Quadrupedal Locomotion over Challenging Terrain》-2020
《Learning robust perceptive locomotion for quadrupedal robots in the wild》-2022
《Whole-Body MPC and Online Gait Sequence Generation for Wheeled-Legged Robots》-轮足款

## 2.3 以电机腿、MPC算法闻名达到四足机器人最快移动速度的MIT Cheetah
论文：
《Dynamic Locomotion in the MIT Cheetah 3 Through Convex Model-Predictive Control》-2018 MPC

## 2.4 以强化学习为主自主生成新动作的浙江大学 绝影
论文：
《Multi-expert learning of adaptive legged locomotion》-2020

## 2.5 国内商业化目前最好的四足机器人宇树科技 GO1

# 3 技术资料学习平台
## 3.1 培训第一阶段四足机器人目标：以小跑（trot)步态为目标的开环稳定运动(以下完成可以不涉及建模稳定分析实现机器人正常运动)
步态整理：https://blog.csdn.net/m0_58585940/article/details/121445129
足端可使用的曲线1：https://mp.weixin.qq.com/s?__biz=MzU1NjEwMTY0Mw==&mid=2247509540&idx=1&sn=ccdd2e3dd0e28219a0c41a4193c68f6e&chksm=fbc8df40ccbf56562ebbd1cde21dd0c29396aeee460ff5bb0dc2e774ab374fc7c4410988602b&scene=27
足端可使用的曲线2：https://mp.weixin.qq.com/s?__biz=MzU1NjEwMTY0Mw==&mid=2247509783&idx=1&sn=ead1c4b8490c6bce6e0b797ba8560ff3&chksm=fbc8de73ccbf5765064484893023a37a93269c434ac78cef017f7bd81112699f0cc657810306&cur_album_id=1752870662173458443&scene=189#wechat_redirect
运动学逆解串联腿12自由度：https://www.bilibili.com/video/av714914634/?vd_source=30216de2308cf451749cc50ccb881d29
运动学逆解串联腿8自由度：https://www.bilibili.com/video/BV13T4y1G7qy/?spm_id_from=333.337.search-card.all.click&vd_source=30216de2308cf451749cc50ccb881d29
运动学逆解并联腿8自由度：https://blog.csdn.net/qq_44757551/article/details/106287696

## 3.2 Webots仿真试验平台学习
### 从控制仿真的角度讲（更关注接触效果，仿真原理）推荐Webot和Gazebo
一小时入门：https://www.bilibili.com/video/BV11V411f7ko/?spm_id_from=333.337.search-card.all.click&vd_source=30216de2308cf451749cc50ccb881d29
【优先学习】利用webot内环境搭建12自由度串联四足：https://zhuanlan.zhihu.com/p/527344782
【最终使用】从SW等建模软件导入的一种方法：https://www.guyuehome.com/36794
Webot官网学习文档：https://zhuanlan.zhihu.com/p/527344782

Webot控制器函数介绍：https://zhuanlan.zhihu.com/p/406419561?utm_id=0

# 4 基础知识学习平台
