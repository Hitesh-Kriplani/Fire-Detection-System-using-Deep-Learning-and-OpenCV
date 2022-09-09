# Fire Detection System using Deep Learning and OpenCV  

## File Description  

1. Dataset File: - https://drive.google.com/drive/folders/11i0ax189216LIKQ3BMUJbF1RTIi2dKd-?usp=sharing  
2. Model Implementation: - Fire_Detection_Model.ipynb  
3. Model: - https://drive.google.com/file/d/1j1awnZTvjfapce3sW6J000LCyu0K8FEX/view?usp=sharing  
4. Realtime Demonstration/Working: - live.py  

## How to use:  

Step 1: - To run the model, Make sure that 'live.py' and 'Fire_Detection_Model.h5' are in the same directory. Note: Also make sure that you have latest version of python and pip installed.  
Step 2: - Open terminal in the project directory and run  
```pip install opencv-python tensorflow numpy pillow keras```  
Step 3: - Then, write 'python live.py' in the terminal and press enter. After few seconds, a new python-camera window will open (Make sure the device's camera is not being used by any other service).  

As soon as there is fire (Use significant amount of flame; Performance may vary for small flames like a matchstick or a lighter; Try to bring the flame closer to the camera if that's the case) in front of the camera, the feed will turn black and white imitating an alarm indicating that the model has detected that there is fire in the current frame.  
