# Event-based Camera Datasets

## Survey Papers
- _[Event-based Vision: A Survey](http://rpg.ifi.uzh.ch/docs/EventVisionSurvey.pdf)_, IEEE Trans. Pattern Anal. Machine Intell. (TPAMI), 2020.

## List of Datasets:
- From Real Scenes
    - <a name="DAVIS Data"></a> DAVIS Data  [Dataset](http://rpg.ifi.uzh.ch/davis_data.html) &emsp; size:~10GB <br>
    paper name: _[The event-camera dataset and simulator: Event-based data for pose estimation, visual odometry, and SLAM](https://journals.sagepub.com/doi/full/10.1177/0278364917691115)_, IJRR, 2017.<br>
    features :  to motivate research on new algorithms for high-speed and high-dynamic-range, ground-truth camera poses from a motion-capture,
    a simulator that released open-source to create synthetic event-camera data. <br>
    task: __SLAM__ <br>
    devices：DAVIS240C, motion-capture system
    
  - <a name="EED"></a> EED  [Dataset](http://prg.cs.umd.edu/BetterFlow.html) &emsp; size:59MB <br>
    paper name: _[Event-based Moving Object Detection and Tracking](https://ieeexplore.ieee.org/abstract/document/8593805)_, IROS, 2018.<br>
    features :  objects of multiple sizes moving at different speeds in a variety of lighting conditions indoor <br>
    task: __moving object detection,__ __moving object tracking__<br>
    devices：DAVIS240B
    
  - <a name="MVSEC"></a> MVSEC  [Dataset](https://daniilidis-group.github.io/mvsec) &emsp; size:~30G <br>
    paper name: _[The Multi Vehicle Stereo Event Camera Dataset: An Event Camera Dataset for 3D Perception](https://ieeexplore.ieee.org/abstract/document/8288670)_, IEEE Robot. Autom. Lett.(RA-L), 2018.<br>
    features :  a synchronized stereo pair event based camera system, carried on a handheld rig, flown by a hexacopter, driven on top of a car, and mounted on a motorcycle,in a variety of different illumination levels and environments <br>
    task: __SLAM__ <br>
    devices：DAVIS m346B(stereo), VI-Sensor(stereo), Velodyne Puck LITE,GPS
    
  - <a name="EV-IMO"></a> EV-IMO  [Dataset](http://prg.cs.umd.edu/EV-IMO.html) &emsp; size:~30G <br>
    paper name: _[EV-IMO: Motion Segmentation Dataset and Learning Pipeline for Event Cameras](https://ieeexplore.ieee.org/abstract/document/8968520)_, IROS, 2019.<br>
    features :  32 minutes of indoor recording with up to 3 fast moving objects in the camera field of view, including accurate pixel-wise motion masks, egomotion and ground truth depth. suitable for learning approach for motion segmentation in indoor scenes <br>
    task: __motion segmentation__ <br>
    devices：DAVIS 346C
    
  - <a name="DSEC"></a> DSEC  [Dataset](http://rpg.ifi.uzh.ch/dsec.html) &emsp; size:~150G <br>
    paper name: _[DSEC: A Stereo Event Camera Dataset for Driving Scenarios](https://ieeexplore.ieee.org/abstract/document/9387069)_, IEEE Robot. Autom. Lett.(RA-L),2021. <br>
    features :driving under challenging illumination conditions such as night, sunrise, and sunset <br>
    task: __SLAM__ <br>
    devices: stereo event camera(2x Prophesee Gen3.1), GNSS, LiDAR, stereo RGB camera
    
  - <a name="TUM-VIE"></a> TUM-VIE  [Dataset](https://go.vision.in.tum.de/tumvie) &emsp; size:~300G <br>
    paper name: _[TUM-VIE: The TUM Stereo Visual-Inertial Event Dataset](https://ieeexplore.ieee.org/abstract/document/9636728)_, IROS,2021.
    <br>
    features : handheld and head-mounted sequences in indoor and outdoor environments, including rapid motion during sports and high dynamic range scenarios <br>
    task: __SLAM__<br>
    devices: stereo event camera(2x Prophesee Gen4-CD), motion capture, IMU, stereo RGB camera 
    
  - <a name="EventScape"></a> EventScape  [Dataset](http://rpg.ifi.uzh.ch/RAMNet.html) &emsp; size:~70G <br>
    paper name: _[Combining Events and Frames Using Recurrent Asynchronous Multimodal Networks for Monocular Depth Prediction](https://ieeexplore.ieee.org/abstract/document/9359329)_, RA-L,2021.
    <br>
    features : events, intensity frames, semantic labels, and depth maps recorded in the CARLA simulator <br>
    task: __SLAM，__ __semantic segmentation，__ __depth estimation__<br>
    devices:  CARLA simulator
    
  - <a name="ViViD++"></a> ViViD++  [Dataset](https://visibilitydataset.github.io/) &emsp; size:more than 250min <br>
    paper name: _[ViViD++ : Vision for Visibility Dataset](https://ieeexplore.ieee.org/abstract/document/9760091)_, RA-L,2022.
    <br>
    features : developing robust visual SLAM under poor illumination <br>
    devices1: mono event camera(Handheld DAVIS240C),Thermal,IMU,RGB-D <br>
    devices2: mono event camera(Driving DVXplorer),Thermal,RGB,RTK-GPS,Ouster OS1 LiDAR 
    
  - <a name="EV-IMO2"></a> EV-IMO  [Dataset](http://prg.cs.umd.edu/EV-IMO.html) &emsp; size:~40G <br>
    paper name: _[EVIMO2: An Event Camera Dataset for Motion Segmentation, Optical Flow, Structure from Motion, and Visual Inertial Odometry in Indoor Scenes with Monocular or Stereo Algorithms](https://arxiv.org/abs/2205.03467)_, arxiv, 2022.<br>
    features :  temporal synchronization between sensors, less jitter, and a more efficient npz format <br>
    task: __motion segmentation,__ __SfM,__ __Object Recognition__<br>
    devices：2x Prophesee Gen3， Samsung Gen3, Prophesee ATIS Gen3
    
- From Static Pictures
  - N-Caltech101
  - N-Cars

## Rank by Citations
[EED](#EED)       &emsp; &emsp;     _202_ <br>
[DSEC](#DSEC)      &emsp; &emsp;    _76_ <br>
[TUM-VIE](#TUM-VIE)&emsp; &emsp;    _19_ <br>
[ViViD++](#ViViD++)  &emsp; &emsp;  _12_ <br>

## Related Links
[Teams and researchers in China](https://github.com/LarryDong/EventCameraGroupsCN) <br>
[Event-based Resources](https://github.com/uzh-rpg/event-based_vision_resources)
