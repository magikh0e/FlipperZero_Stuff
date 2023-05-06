# Creating A New Infrared Remote on Flipper Zero

After learning a new set of infrared signal and saving the file to *SD Card/infrared/something.ir*. 

You can now make a UI for the captured IR dump. 
>NOTE: This UI will be accessible under Apps->Tools->IR Remote via the flipper zero device.

## Creating the Remote UI
Begin by creating a new file under *SD Card/infrared/remote*. 

This is the file that maps the buttons of the flipper zero device to functions of the IR dump captured earlier.
>NOTE: This file will go into *SD Card/infrared/remote* access to your custom remote: Apps->Tools->IR Remote 

Example Format
```
REMOTE: /ext/infrared/something.ir
UP: func1
DOWN: func2
LEFT: func3
RIGHT: func4
OK: 
BACK:  
UPHOLD:   
DOWNHOLD:   
```

The func1-4 refrenced above are just examples, you need to know the name of the address and commands that were captured earlier.
>NOTE: you can find the .ir file saved earlier at *SD Card/infrared/something.ir*

Example of *SD Card/infrared/something.ir*
```
Filetype: IR signals file
Version: 1
# 
name: func1
type: parsed
protocol: NEC
address: 01 00 00 00
command: 1B 00 00 00
# 
name: func2
type: parsed
protocol: NEC
address: 01 00 00 00
command: 09 00 00 00
# 
name: func3
type: parsed
protocol: NEC
address: 01 00 00 00
command: 04 00 00 00
# 
name: func4
type: parsed
protocol: NEC
address: 01 00 00 00
command: 07 00 00 00
# 
```

Once the something.txt file has been created and mapped to your captured Infrared dump, you can test your remote by going to *Apps->Tools->IR Remote* on your F0 device
