# Holography

Simple demo of WebXR and Deep Learning using Tensorflow to create holograms on-the-fly. 
It works on Android with the last Chrome (>= r81)

![alt text](https://raw.githubusercontent.com/nosy-b/holography/master/demo.gif "Holography")

DEMO here: http://nosy-b.github.io/holography

## How to

- First be sure to have an android phone with chrome >=r81
- Choose your camera feed (ideally back camera)
- Tap on start AR (the position of your phone at that moment will be the center of the frame)
- Move a bit around if you want to help the space detection
- Look at a human (real or a photo) and tap on the screen
- It should appear coming from your phone to the direction you were looking at when clicked on Start (initial position)

## Description

Small code that create particles for people extracted from camera feed using Bodypix model
Feel free to use this dirty little code for your own experiments
I put demos on my twitter sometimes  https://twitter.com/AlexandreDevaux

## Getting Started

### Dependencies

* ThreeJS, TensorFlowJS


## Help

One thing to be careful about is not to frame too close the subject you want to make a hologram of. The camera frame is smaller than what your screen shows. (A good todo would be to show camera frame while in AR)

## Authors

Alexandre Devaux 
[@AlexandreDevaux](https://twitter.com/AlexandreDevaux)

## Version History



## License

Check the license of THREEJS and Tensorflow

