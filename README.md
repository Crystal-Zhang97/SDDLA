# SDDLA
### Title:Shape-Dependent Dynamic Label Assignment for Oriented Remote Sensing Object Detection
<p align="center"> <img src="overview.png" width="100%"></p>


## Results
1. DOTA_1.0
|Model           |    Backbone     |    MS  |   mAP  | Download|
|:--------------:| :-------------: | :-----:| :----: |  :---------------------------------------------------------------------------------------: |
|RetinaNet+SDDLA |    R-101-FPN    |   -    |  73.35 | [model](https://pan.baidu.com/s/1aspypaz8a7QvFyUdDR986g)     |
|RetinaNet+SDDLA |    R-101-FPN    |   √    |  79.10 | [model](https://pan.baidu.com/s/1VPsAB3Kb90IqJTluH6lFHw)     |
|S2A-Net+SDDLA   |    R-101-FPN    |   √    |  79.92 | [model](https://pan.baidu.com/s/1VPsAB3Kb90IqJTluH6lFHw)     |

## Preparations
Note: mmcv>=1.3.17, <=1.8.0
- Linux
- Python 3.7
- PyTorch 1.12
- cudatoolkit 11.6
- mmrotate 0.3.4
### Place the file sd_assigner.py into the path "mmrotate\core\bbox\assigners" , the sdla_rotated_retina_head.py into the path "mmrotate\models\dense_heads"
