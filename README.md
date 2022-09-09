# Fire Detection System using Deep Learning and OpenCV

## File Description

1. Dataset File: - https://drive.google.com/drive/folders/11i0ax189216LIKQ3BMUJbF1RTIi2dKd-?usp=sharing
2. Model Implementation: - Fire_Detection_Model.ipynb
3. Model: - https://drive.google.com/file/d/1j1awnZTvjfapce3sW6J000LCyu0K8FEX/view?usp=sharing
4. Realtime Demonstration/Working: - live.py

## How to use:

Step 1: - To run the model, just download: 'live.py' and 'Model' (Make sure they are in the same directory)  
Step 2: - Open terminal in the project directory and run  
```pip install opencv-python tensorflow numpy pillow keras```  
Step 3: - Write 'python live.py' in the terminal and after few seconds, a new python-camera window will open.

As soon as there is fire (Use significant amount of flame; It may or may not work for Matchstick flames) in front of the camera, the feed will turn black and white indicating that the model has detected that there is fire in the current frame.
