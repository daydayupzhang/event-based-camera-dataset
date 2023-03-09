# Event-based Camera Datasets

## Survey Papers
- _[Event-based Vision: A Survey](http://rpg.ifi.uzh.ch/docs/EventVisionSurvey.pdf)_, IEEE Trans. Pattern Anal. Machine Intell. (TPAMI), 2020.

## List of Datasets:
- From Real Scenes
  - <a name="EED"></a> EED  [Dataset](http://prg.cs.umd.edu/BetterFlow.html) &emsp; size:59MB <br>
    paper name: _[Event-based Moving Object Detection and Tracking](https://ieeexplore.ieee.org/abstract/document/8593805)_, IROS, 2018.<br>
    features :  objects of multiple sizes moving at different speeds in a variety of lighting conditions indoor <br>
    devices：DAVIS240B
    
  - <a name="MVSEC"></a> MVSEC  [Dataset](https://daniilidis-group.github.io/mvsec) &emsp; size:27G <br>
    paper name: _[The Multi Vehicle Stereo Event Camera Dataset: An Event Camera Dataset for 3D Perception](https://ieeexplore.ieee.org/abstract/document/8288670)_, IEEE Robot. Autom. Lett.(RA-L), 2018.<br>
    features :  a synchronized stereo pair event based camera system, carried on a handheld rig, flown by a hexacopter, driven on top of a car, and mounted on a motorcycle,in a variety of different illumination levels and environments <br>
    devices：DAVIS m346B(stereo), VI-Sensor(Skybotix stereo camera), Velodyne Puck LITE(VLP-16 PUCK LITE),GPS(UBLOX NEO-M8N)
    
  - <a name="DSEC"></a> DSEC  [Dataset](http://rpg.ifi.uzh.ch/dsec.html) &emsp; size:more than 152G <br>
    paper name: _[DSEC: A Stereo Event Camera Dataset for Driving Scenarios](https://ieeexplore.ieee.org/abstract/document/9387069)_, IEEE Robot. Autom. Lett.(RA-L),2021. <br>
    features :driving under challenging illumination conditions such as night, sunrise, and sunset <br>
    devices: GNSS(U-Blox RTK GNSS Receiver), LiDAR(Velodyne VLP-16), stereo event camera(2x Prophesee Gen3.1),stereo RGB camera(2x FLIR Blackfly S USB3) 
    
  - <a name="TUM-VIE"></a> TUM-VIE  [Dataset](https://go.vision.in.tum.de/tumvie) &emsp; size:more than 300G <br>
    paper name: _[TUM-VIE: The TUM Stereo Visual-Inertial Event Dataset](https://ieeexplore.ieee.org/abstract/document/9636728)_, IROS,2021.
    <br>
    features : handheld and head-mounted sequences in indoor and outdoor environments, including rapid motion during sports and high dynamic range scenarios <br>
    devices: motion capture(MoCap OptiTrack Flex13), IMU(Bosch BMI160), stereo event camera(2x Prophesee Gen4-CD),stereo RGB camera(2x IDS Camera uEye) 
    
  - <a name="ViViD++"></a> ViViD++  [Dataset](https://visibilitydataset.github.io/) &emsp; size:more than 250min <br>
    paper name: _[ViViD++ : Vision for Visibility Dataset](https://ieeexplore.ieee.org/abstract/document/9760091)_, RA-L,2022.
    <br>
    features : developing robust visual SLAM under poor illumination <br>
    devices: mono event camera(Handheld DAVIS240C),Thermal,IMU,RGB-D; mono event camera(Driving DVXplorer),Thermal,RGB,RTK-GPS,Ouster OS1 LiDAR 
    
- From Static Pictures
  - N-Caltech101
  - N-Cars

## Rank by Citations
[EED](#EED)       &emsp; &emsp;     _202_ <br>
[DSEC](#DSEC)      &emsp; &emsp;    _76_ <br>
[TUM-VIE](#TUM-VIE)&emsp; &emsp;    _19_ <br>
[ViViD++](#ViViD++)  &emsp; &emsp;  _12_ <br>
