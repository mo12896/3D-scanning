# 3D-scanning
Different approaches for 3D-reconstrcutions using a photogrammetry pipeline:

###1. Photogrammetry, using KScan3D
- Turotial: https://www.youtube.com/watch?v=CV1Vluz0rPY&t=102s
- Software: [KScan3D](https://kscan3d.software.informer.com/) \
... use [Meshmixer](https://www.meshmixer.com/) of Fusion 360 to fill missing spaces
- Sensor: Depth Camera (e.g. Kinect)

###2. Photogrammetry, using Meshroom or COLMAP
- Turotials: 
    - https://www.youtube.com/watch?v=45D0pFdqVgw 
    - https://www.youtube.com/watch?v=ye-C-OOFsX8  
- Software: [Meshroom](https://alicevision.org/#meshroom) or [COLMAP](https://colmap.github.io/) \
... use [Meshlab](https://www.meshlab.net/#download) to correct for artefacts
- Sensor: Monocular Camera (e.g. Smartphone Camera)

###3. Photogrammetry, using the Qlone App 
- Software: Qlone App
- Sensor: Monocular Camera (e.g. Smartphone Camera) \
... use the provided [calibration mat](./assets/qloneMat.pdf)!