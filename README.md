<!--
 * @Author: zhanghao
 * @Date: 2022-05-30 22:29:25
 * @LastEditTime: 2022-05-30 22:48:16
 * @FilePath: \particle_filter_localization\README.md
 * @Description: 2022年5月30日22:30:05
-->
# 粒子滤波学习记录
先进控制系统课程分享，准备复现一下粒子滤波的相关代码。分为两部分：
- windows下的两个matlab代码和一个python代码
- linux下的二维栅格地图下粒子滤波实现移动机器人定位
## 1. windows
三套代码
1. windows\粒子滤波matlab实现（三套）\particle_filter_demo\particle_filter_demo-master\particle_filter.py
2. windows\粒子滤波matlab实现（三套）\particle_filter_demo\PF_Video_EN\particle_filter_by_saved_movie.m
3. windows\粒子滤波matlab实现（三套）\particle_filter_demo\Particle_filter_SIR_demo1.m
> CSDN 白巧克力亦唯心：Particle Filter Tutorial 粒子滤波：从推导到应用（一）~（四）

## 2. linux
# Particle Filter Localization
## Particle filter-based localization in an occupancy grid map.
For details, please refer to：https://zhuanlan.zhihu.com/p/43523632

Dataset：https://pan.baidu.com/s/1j_SSEtaq7D0XwaED0Jg4Ew

## Demo

STEP1. Download the repository to your ROS workspace：catkin_ws/src

STEP2. Make：catkin_make

STEP3. Run: roslaunch particle_filter_localization pf_localization.launch

STEP4. Play a rosbag: rosbag play laser1_2018-07-14-17-31-41.bag -r 2
