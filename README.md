# Wind_Turbine_Inspection
Used dataset from https://orbit.dtu.dk/en/publications/dtu-drone-inspection-images-of-wind-turbine and annotated using roboflow.
I have annoated faults in the images  named:
  1.Cracks:If a turbine fin is broken I have labelled them as Cracks
  2.Dirt:If I found some dirt on turbines I have annotated them using dirt class.
  3.Damge:If I  found some damage other than a crack ,i have annoated them using damage class
  4.Errosion: If i found rust on any part of the turbine i have annotated them using errosion class
  PS:We can create our own class in Roboflow
Then after annotation I  preprocessed images into the size 640x640 ,added some augmentation Like zoom in images ,noise.
Used Yolov8 custom model to detect faults in the google colaboratory.
