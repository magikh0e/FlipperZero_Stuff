# Creating A New Infrared Remote on Flipper Zero

Apps->Tools->IR Remote

Access your remotes by going to Apps->Tools->IR Remote on the F0 device

After learning a new infrared remotes buttons and saving the file to SD Card/infrared/something.ir. 
You can now make a UI for the captured IR dump. 
>NOTE: This UI will be accessible under Apps->Tools->IR Remote via the flipper zero device.

Begin by creating a new file under SD Card/infrared/remote. 
This is the file that maps the buttons of the flipper zero device to functions of the IR dump captured earlier.

Example Format
REMOTE: /ext/infrared/something.ir
UP: func1
DOWN: func2
LEFT: func3
RIGHT: func4
OK: 
BACK:  
UPHOLD:   
DOWNHOLD:   