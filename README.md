**描述**：
不依赖 ROS, Ceres, G2o。主要有基于 Eigen 的后端 LM 算法，滑动窗口等算法
该代码支持 Ubuntu or Mac OS.


## 主要的代码在src/estimator里，根据一些理论推的公式写出来的计算流程
## 当然一些初始化的东西，比如initialize_sfm，这些都是相对比较基础的，自己写的


### 安装依赖项：

1. pangolin: <https://github.com/stevenlovegrove/Pangolin>

2. opencv

3. Eigen

4. Ceres: vins 初始化部分使用了 ceres 做 sfm，所以我们还是需要依赖 ceres. 

