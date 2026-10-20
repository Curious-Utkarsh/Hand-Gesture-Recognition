# Hand Gesture Recognition — MediaPipe + OpenCV

Train your own hand gestures from the webcam and recognise them in real time. MediaPipe Hands gives 21 landmarks per hand; the script records labelled landmark sets, saves them with `pickle`, and matches live hands against them. Computer-vision learning project, 2022.

![Hand gesture recognition](https://user-images.githubusercontent.com/105288469/187017874-a16ec95e-8bf8-40cb-8ebe-73091cccc986.gif)

**Stack:** Python · OpenCV · MediaPipe · NumPy

**Run:** `python "Hand Gesture Recognition.py"` → enter `1` to train gestures, `0` to recognise.

**Also with hand tracking:** [Hill Climb Racing controlled by hand gestures (video)](https://youtu.be/dk9JOpsxH-o)

**Where this led:** hand tracking later drove robots — [IMU gesture robot](https://github.com/MechaMind-Labs/microros-gesture-robot), [UR5 MediaPipe pick-and-place](https://github.com/MechaMind-Labs/ur5-gesture-pick-and-place) and two-hand teleop of my [SCARA arm](https://github.com/Curious-Utkarsh/scara-pick-and-place).

---
[Kumar Utkarsh](https://github.com/Curious-Utkarsh) · [Portfolio of builds](https://www.mechamindlabs.com/projects)
