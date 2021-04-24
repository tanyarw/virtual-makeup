# Virtual Makeup

Apply virtual layer of make-up on an image using python.

## Face detection
Detect face in the image using Haar cascade (frontal face)

## Face landmark features 
Detect required landmark features on the face using dlip plots
- outer lip coordinates
- inner lip coordinates
- mid of face
- left cheek boundary
- right cheek boundary

![arch](./facial_landmarks.jpg)

## Apply the "makeup"
- Interpolate the boundary with scipy
- Plot the colors using skimage and cv2
