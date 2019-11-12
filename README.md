# 流行的SLAM研究方向
## 第一部分：特征的定义
### 一、点特征
#### 1、错误对应问题
  解决方案：深度学习
  + superpoint(github上有代码）
  + gcnv2
#### 2、运算时间过长
  解决方案：在不算描述子的情形下进行对应
  + RK-SLAM
  + SVO
### 二、直接法
#### 1、光照的变化带来的成像噪声
  解决方案：  
  + NID-SLAM
#### 2、Rolling Shutter问题
  解决方案：
  + DSO with Rolling Shutter
#### 3、需要深度信息
  解决方案：深度学习学习深度
   + CODE-SLAM
   + Learning Meshes for dense Visual Slam（CODE-SlAM的后续）
   + deep virtual DSO
#### 4、单目求深度
  解决方案：
