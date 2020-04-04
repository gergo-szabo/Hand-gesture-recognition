# Hand gesture recognition

I was commissioned to make a hand gesture detector demo for a webpage from an existing Github repo. That model was horribly overfit so I decided to make my own. [Google MediaPipe](https://github.com/google/mediapipe) models provide the hand and hand keypoint detection. My hand gesture detector uses the keypoint coordinates to guess the intended sign.

<img src="readme_imgs/metal.png" height="200"> <img src="readme_imgs/stop.png" height="200">

<img src="readme_imgs/ok.PNG" height="150"> <img src="readme_imgs/peace.png" height="150">
