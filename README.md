# car_speed_check_opencv
Detect car speeds in a video using OpenCV and dlib

Technologies used :
- Python
- opencv
- dlib
<br>

Sub tasks :
----------
1. Car Detection
    - We are using Haarcascade classifier to identify vehicles.
2. Car Tracking - ( assigning IDs to vehicles )
    - We have used corelation tracker from dlib library.
3. Speed Calculation
    - We are calculating the distance moved by the tracked vehicle 
		  in a second, in terms of pixels, so we need pixel per meter
		  to calculate the distance travelled in meters.
	- With distance travelled per second in meters, we will get the 
		  speed of the vehicle.
