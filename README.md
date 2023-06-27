# MMFnet

## Introduce
Fusing LiDAR and camera information is important for achieving accurate and reliable 3D object detection in autonomous driving systems.

## Start
### Data Preparation
The following directory structure will be seen:
```
MMFnet
├── dataset
│   ├── ImageSets
│   │   ├── test.txt
│   │   ├── train.txt
│   │   ├── trainval.txt
│   │   ├── val.txt
│   ├── testing
│   │   ├── calib
│   │   ├── image_2
│   │   ├── velodyne
│   │   ├── label_2
│   ├── training
│   │   ├── calib
│   │   ├── image_2
│   │   ├── velodyne
│   │   ├── label_2
```
### Model Preparation
DGCNN is from https://github.com/muhanzhang/pytorch_DGCNN, and ResNet-34 is from https://github.com/GohVh/resnet34-unet.git.
### Training and Evaluation
sh ./tools/train.sh
sh ./tools/test.sh

### Results
