<!--
 * @Author: zhanghao
 * @Date: 2022-05-30 22:29:25
 * @LastEditTime: 2022-05-30 22:33:37
 * @FilePath: \particle_filter_localization\README.md
 * @Description: 2022年5月30日22:30:05
-->
# 粒子滤波学习记录
## 1. CSDN 白巧克力亦唯心：Particle Filter Tutorial 粒子滤波：从推导到应用（一）~（四）












# Particle Filter Localization
## Particle filter-based localization in an occupancy grid map.

For details, please refer to：https://zhuanlan.zhihu.com/p/43523632

Dataset：https://pan.baidu.com/s/1j_SSEtaq7D0XwaED0Jg4Ew

## Demo

STEP1. Download the repository to your ROS workspace：catkin_ws/src

STEP2. Make：catkin_make

STEP3. Run: roslaunch particle_filter_localization pf_localization.launch

STEP4. Play a rosbag: rosbag play laser1_2018-07-14-17-31-41.bag -r 2
# 测试
2022年5月30日测试更改