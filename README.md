# Event-based Camera Datasets

## Survey Papers
- _[Event-based Vision: A Survey](http://rpg.ifi.uzh.ch/docs/EventVisionSurvey.pdf)_, IEEE Trans. Pattern Anal. Machine Intell. (TPAMI), 2020.

## List of Datasets:
- From Real Scenes
  - <a name="EED"></a> EED  &emsp; size:10G
    [Dataset](http://prg.cs.umd.edu/BetterFlow.html) <br>
    paper name: _[Event-based Moving Object Detection and Tracking](https://ieeexplore.ieee.org/abstract/document/8593805)_, IROS, 2018.<br>
    features :  _objects of multiple sizes moving at different speeds in a variety of lighting conditions_ _indoor_ <br>
    devices：DAVIS240B
    
  - <a name="MVSEC"></a> MVSEC  &emsp; size:10G
    [Dataset](https://daniilidis-group.github.io/mvsec) <br>
    paper name: _[The Multi Vehicle Stereo Event Camera Dataset: An Event Camera Dataset for 3D Perception](https://ieeexplore.ieee.org/abstract/document/8288670)_, IEEE Robot. Autom. Lett.(RA-L), 2018.<br>
    features :  _ a synchronized stereo pair event based camera system, carried on a handheld rig, flown by a hexacopter, driven on top of a car, and mounted on a motorcycle,in a variety of different illumination levels and environments_ <br>
    devices：DAVIS m346B, VI-Sensor(Skybotix integrated VI-sensor,stereo camera), Velodyne Puck LITE(VLP-16 PUCK LITE),GPS(UBLOX NEO-M8N)
    
  - <a name="DSEC"></a> DSEC  &emsp; size:10G
    [Dataset](http://rpg.ifi.uzh.ch/dsec.html) <br>
    paper name: _[DSEC: A Stereo Event Camera Dataset for Driving Scenarios](https://ieeexplore.ieee.org/abstract/document/9387069)_, IEEE Robot. Autom. Lett.(RA-L),2021.
    <br>
    features :_driving under challenging illumination conditions such as night, sunrise, and sunset_ <br>
    devices: GNSS(U-Blox RTK GNSS Receiver), LiDAR(Velodyne VLP-16), stereo event camera(2x Prophesee Gen3.1),stereo RGB camera(2x FLIR Blackfly S USB3) 
    
  - <a name="TUM-VIE"></a> TUM-VIE  &emsp; size:10G
    [Dataset](https://go.vision.in.tum.de/tumvie) <br>
    paper name: _[TUM-VIE: The TUM Stereo Visual-Inertial Event Dataset](https://ieeexplore.ieee.org/abstract/document/9636728)_, IROS,2021.
    <br>
    features :_ handheld and head-mounted sequences in indoor and outdoor environments, including rapid motion during sports and high dynamic range scenarios_ <br>
    devices: IR(MoCap OptiTrack Flex13), IMU(Bosch BMI160), stereo event camera(2x Prophesee Gen4-CD),stereo RGB camera(2x IDS Camera uEye) 
    
- From Static Pictures
  - N-Caltech101
  - N-Cars

## Rank by Citations
[EED](#EED)       &emsp; &emsp;     _202_ <br>
[DSEC](#DSEC)      &emsp; &emsp;    _76_
