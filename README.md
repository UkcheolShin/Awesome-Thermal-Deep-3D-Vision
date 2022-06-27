<!--A curated list of resources for deep 3D vision from thermal image-->
<!-- PROJECT LOGO -->

<p align="center">
  <h1 align="center">Awesome-Thermal-Deep-3D-Learning</h1>
  <p align="center">A curated list of resources for deep 3D vision from thermal image
  </p>
</p>

<h2>Table of contents</h2>

- [1. Dataset for Thermal 3D Vision](#1-dataset-for-thermal-3d-vision)
- [2. Deep 3D Vision from Thermal Image](#2-deep-3d-vision-from-thermal-image)
  - [2.1 Supervised 3D Vision](#21-supervised-3d-vision-from-thermal-image)
  - [2.2 Self-supervised 3D Vision](#22-self-supervised-3d-vision-from-thermal-image)
- [3. Deep 3D Vision from Thermal and Additional Sensor Fusion](#3-deep-3d-vision-from-thermal-and-additional-sensor-fusion)
- [4. Non-Deep 3D Vision from Thermal and Other Sensor](#4-non-deep-3d-vision-from-thermal-and-other-sensor)

# 1. Dataset for Thermal 3D Vision

<h2>Dataset List</h2>

|Publication|Title|Sensor|Platform|Scene Types|Dataset Link|Highlight|
|-|-|-|-|-|-|-|
CVPR 17 | [CATS: A Color And Thermal Stereo Benchmark](https://openaccess.thecvf.com/content_cvpr_2017/papers/Treible_CATS_A_Color_CVPR_2017_paper.pdf) | Stereo RGB, Stereo Thermal, Lidar | Handheld | In+Outdoor | [Here](http://bigdatavision.org/cats/)| |
ITS 19 | [KAIST Multi-Spectral DayNight Data Set for Autonomous and Assisted Driving](https://ieeexplore.ieee.org/document/8293689) | Co-aligned RGB/Thermal, Stereo RGB, Lidar, GPS/IMU | Vehicle | Outdoor | Here | Large-scale outdoor dataset |
ICRA 21 | [A Multi-spectral Dataset for Evaluating Motion Estimation Systems](https://arxiv.org/abs/2007.00622) | RGB, Thermal, Kinect, IMU | Handheld | In+Outdoor | [Here](https://github.com/NGCLAB/multi-spectral-dataset)| Large-scale indoor datase|
RA-L 22 | [ViViD++: Vision for Visibility Dataset](https://arxiv.org/abs/2204.06183) | RGB-D, Thermal, Lidar, GPS/IMU, Event | Handheld, Vehicle | In+Outdoor| [Here](https://visibilitydataset.github.io/) | Large-scale outdoor dataset |
Arxiv 22 | [OdomBeyondVision; An Indoor Multi-modal Multi-platform Odometry Dataset Beyond the Visible Spectrum](https://arxiv.org/abs/2206.01589) | RGB, Thermal, Lidar, IMU, Radar | Handheld, UGV, UAV | Indoor | [Here](https://github.com/MAPS-Lab/OdomBeyondVision) | Large-scale indoor dataset|
---


# 2. Deep 3D Vision from Thermal Image

## 2.1 Supervised 3D Vision from Thermal Image

<h2>Paper List</h2>

|Publication|Title|Task|Dataset|Scene Types|Code|Highlight|
|-|-|-|-|-|-|-|

---
## 2.2 Self-Supervised 3D Vision from Thermal Image

<h2>Paper List</h2>

|Publication|Title|Task|Dataset|Scene Types|Code|Highlight|
|-|-|-|-|-|-|-|
AAAI 18 | [Multispectral Transfer Network: Unsupervised Depth Estimation for All-Day Vision](https://ojs.aaai.org/index.php/AAAI/article/view/12297) | MonoDepth | KAIST Multi-Spectral Dataset | Outdoor | Here | Spatial RGB, thermal image reconstruction | 
WACV 21 | [An Alternative of LiDAR in Nighttime: Unsupervised Depth Estimation Based on Single Thermal Image](https://openaccess.thecvf.com/content/WACV2021/papers/Lu_An_Alternative_of_LIDAR_in_Nighttime_Unsupervised_Depth_Estimation_Based_WACV_2021_paper.pdf) | MonoDepth | Own dataset | In+Outdoor | here | Utilize spatial thermal image reconstruction |
RA-L 21 | [SuperThermal: Matching Thermal as Visible Through Thermal Feature Exploration](https://ieeexplore.ieee.org/abstract/document/9359356) | Feature Matching | CSS, KAIST pedestrian | Outdoor | Here | TBA | 
RA-L 22& ICRA 22 | [Self-Supervised Depth and Ego-Motion Estimation for Monocular Thermal Video Using Multi-Spectral Consistency Loss](https://ieeexplore.ieee.org/abstract/document/9662239) | MonoDepth, Pose | [ViViD](https://visibilitydataset.github.io/) | In+Outdoor | [Here](https://github.com/UkcheolShin/ThermalSfMLearner-MS) | Utilize Temporal RGB, thermal image reconstruction loss |
RA-L 22& IROS 22 | [Maximizing Self-supervision from Thermal Image for Effective Self-supervised Learning of Depth and Ego-motion](https://arxiv.org/abs/2201.04387) | MonoDepth, Pose | [ViViD](https://visibilitydataset.github.io/) | In+Outdoor | [Here](https://github.com/UkcheolShin/ThermalMonoDepth) | Utilize temporal thermal image reconstruction only |
--- 



# 3. Deep 3D Vision from Thermal and Additional Sensor Fusion

<h2>Paper List</h2>

|Publication|Title|Task|Sensor|Dataset|Scene Types|Code|Highlight|
|-|-|-|-|-|-|-|-|
RA-L 20 | [DeepTIO: A Deep Thermal-Inertial Odometry With Visual Hallucination](https://ieeexplore.ieee.org/abstract/document/8968430) | Odometry | Thermal, IMU | Own dataset | Here | TBA | TBA |
IROS 20 | [Tp-tio: A robust thermal-inertial odometry with deep thermalpoint](https://ieeexplore.ieee.org/abstract/document/9341716) | Odometry | Thermal, IMU | TBA | TBA |  TBA | TBA |
TRO 21 | [Graph-Based Thermal–Inertial SLAM With Probabilistic Neural Networks](https://ieeexplore.ieee.org/abstract/document/9623261)| Odometry | Thermal, IMU | TBA | TBA | TBA | TBA |

---

# 4. Non-Deep 3D Vision from Thermal and Other Sensor

<h2>Paper List</h2>

|Publication|Title|Task|Sensor|Dataset|Scene Types|Code|Highlight|
|-|-|-|-|-|-|-|-|
IROS 21 | [Radar Visual Inertial Odometry and Radar Thermal Inertial Odometry: Robust Navigation even in Challenging Visual Conditions](https://ieeexplore.ieee.org/abstract/document/9636799)| Odometry | Thermal, IMU, Radar | TBA | TBA | TBA | TBA |
CVPR 21 | [Shape from Thermal Radiation:Passive Ranging Using Multi-spectral LWIR Measurements](https://openaccess.thecvf.com/content/CVPR2022/html/Nagase_Shape_From_Thermal_Radiation_Passive_Ranging_Using_Multi-Spectral_LWIR_Measurements_CVPR_2022_paper.html) | MonoDepth | Thermal | Own dataset | In+Outdoor | Here | TBA |
---
