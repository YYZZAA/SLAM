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
   + Learning Meshes for dense Visual SLAM（CODE-SLAM的后续）
   + deep virtual DSO
#### 4、单目求深度
  解决方案：
  + popup SLAM
### 三、结构化特征
  + 线、边、面
  + 建筑结构： Struct SLAM
  + 灭点
### 四、语义信息
  + Object-Level： 将视觉元素定义为 Object
  + 利用语义分割约束特征的对应
### 五、新的传感器
  + 全景相机
  + 多相机系统
  + 多agent联合建图
  + 光场相机
  + Event Camera
  + 高帧率、高分辨率相机
## 第二部分：求解框架
### 一、滤波法的累积误差
  + A Linear Complexity EKF for Visual Inertial navigation with Loop Closures
### 二、优化方法的计算速度
  + 增量优化
  + Marginalization
  + rotation average：对应论文 Why bundle adjustment
  + 关键帧选择
### 三、基于深度学习的精度及泛化能力及地图的表示
### 四、拓扑地图、场景中物体的拓扑关系
### 五、深度学习和传统方法的融合
## 第三部分：和其他传感器的融合
## 第四部分：闭环检测、重定位
### 一、跨季节，跨天气、光照变化、场景微小变化
### 二、重复纹理
