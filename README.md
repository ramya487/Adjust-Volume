# Adjust-Volume
A Python Program to adjust volume upon hand gesture
### Working
First the video frame is captured using cv2 converted to rgb. mediapipe is used to detect the hand gestures check if there are any hand landmarks if yes draw points and connections. The coordinates of the index finger and the thumb finger are used to determine whether the volume must be increased or decreased using pyautogui library
