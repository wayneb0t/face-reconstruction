# 3D Face Reconstruction (CS231A final project)
An implementation of Bregler et al.'s factorization method for non-rigid structure for motion, combined with automated facial landmarking to create a 3D facial reconstruction pipeline

## Requirements
Requires Python bindings for OpenCV, Python bindings for dlib, numpy, matplotlib, and imutils. Also requires dlib's pretrained [68-point face landmarker](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2).

## Example results
![Original video](original.gif)
![Landmarked video](landmarked.gif)
![Reconstructed video](reconstruction.gif)
