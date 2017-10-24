# Pascip.github.io

-------------Swag Cam-------------

Was made for testing, accesses your devices camera and takes a new photo every 5 seconds. 

No external script because it was simpler to show in one file (also those two files would be even shorter). 

# Video element
It shows a live picture of the camera. Works fine expect for Mobile Users that use Chrome, because it won't update the picture always.

# Canvas element
It shows the latest pic as an image, so you are able to right click and download it. 

# The script
The most important part about that script is the snap function. It takes the video height and width and sets the canvas equal to it, 
and after that it starts to draw the image. 

Since the script should just do a new photo every 5 seconds we repeat the function thingToRepeat repeat every 5 seconds. 
