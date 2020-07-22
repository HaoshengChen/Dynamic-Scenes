# Dynamic Scenes Dataset for Visual Loop Closure Detection

![image](https://github.com/HaoshengChen/Dynamic-Scenes/blob/master/pics/DynamicScenes.png)

The "Dynamic Scenes" Dataset is provided for testing visual loop closure detection algorithms in highly dynamic scenes. It has a strong background in some crucial applications such as autonomous driving systems.

The dataset was captured in the central commercial district of a city of ten million people. The “Dynamic Scenes” dataset contains two sequences as shown in the figure above. The first one, which was acquired by traveling around a lake as the blue trajectory, named “Road Ring.”  The other sequence, named “CBD,” was acquired by traveling around a business district, and is depicted by the red and green trajectories.

The entire dataset was recorded by a [ZED](https://github.com/stereolabs) stereo camera at 1280 × 460 resolution @ 60fps.

The loop closure ground truth is formatted as two similarity matrices in the MAT files.

Note that the "Dynamic Scenes" dataset also can be used for testing localization or image retrieval algorithms as well.

## Road Ring

![image](https://github.com/HaoshengChen/Dynamic-Scenes/blob/master/pics/0006412.png)

* Download [Road Ring](https://drive.google.com/open?id=19ixy0msqR6z2BgnNo4XGeUH4ngYJMLq8) sequence from google drive. 

## CBD

![image](https://github.com/HaoshengChen/Dynamic-Scenes/blob/master/pics/0006395.png)

* Download [CBD](https://drive.google.com/open?id=1uN85OZjUY4azK51j0QfUIGHc27yOFwuW) sequence from google drive. 

## Citation

If you use this dataset, please cite our paper:

```
@ARTICLE{hschen2020,
  author={H. {Chen} and G. {Zhang} and Y. {Ye}},
  journal={IEEE Transactions on Industrial Informatics}, 
  title={Semantic Loop Closure Detection with Instance-Level Inconsistency Removal in Dynamic Industrial Scenes}, 
  year={2020},
  pages={1-1},}
```

or

```
H. Chen, G. Zhang and Y. Ye, "Semantic Loop Closure Detection with Instance-Level Inconsistency Removal in Dynamic Industrial Scenes," in IEEE Transactions on Industrial Informatics, doi: 10.1109/TII.2020.3010580.
```
