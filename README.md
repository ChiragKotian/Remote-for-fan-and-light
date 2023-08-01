# Remote for fan and light
Imagine feeling cold but having no means to slow down the fan in your room as the fan you have in your room is controlled via an IR remote, but the remote is nowhere to be seen.

I had the same problem, so I made a remote for the fan and lights in my room myself.

![remotefanlight](https://github.com/ChiragKotian/Remote-for-fan-and-light/assets/117931123/8d70823f-fc00-491d-a931-bc0584fdfb2c)

## Engineering Description:
The system consists of Arduino uno as the main processing unit. A joystick takes user input (along the y-axis fan speeds up on +y and fan slows down on -y. Similarly, for lights, it's along the x-axis(horizontal)). This info is then converted to IR pulses determined after analysing signals sent by the original remote (Using Arduino and IR receiver) and transmitted using an IR LED. A buzzer and an RGB LED give feedback to the user that 
 the command is transmitted (two short beeps and a green light indicate an increase, and one long beep and a red light indicate a decrease.).

 ## For more details check out [this](https://youtu.be/eoylrCKNo1c) youtube video.

## Credits:

_This project was solely made by [me](https://github.com/ChiragKotian) as a side project_
