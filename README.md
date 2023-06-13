# autonomous-vehicle-algo
Algorithm of an autonoums vehicle that performs basic functions like edge detection, target tracking, searching and retrival. 
The autonomous vehicle primary function is to detect the presence of a tennis-sized ball, collect it and return it to the designated area.
The main functions performs the main tasks required by the vehecle.
The Sub functions enchances and supports the vehicle when it performs the main tasks.

# Background
The algorithm is written in C prgoramming languague through the platform 'RobotC'. The code is installed and work with customized and designed Vex robot to perform the 
above mentioned functions.

# Main fucntion
findBall(): orientate vehicle and move it to find ball on the field.
collectBall(): moves the vehicle to the detected ball and retrived the ball.
releaseBall(): moves the vehicle to designate area before releasing ball.

# Sub functions
detectYellow()
detectYellow2()
oppVehicleStatus()
detectVehicle()
CaptureDirections()
faceSouth()
