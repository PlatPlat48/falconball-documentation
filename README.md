# Super Monkey Ball 3 (Falcon Ball)

<iframe src="https://drive.google.com/file/d/1DUg0XQv8CPKBA6sZ_P78x3E6aWkN5Des/preview" width="640" height="480"></iframe>

If the video doesn't work, click the link: https://drive.google.com/file/d/1DUg0XQv8CPKBA6sZ_P78x3E6aWkN5Des

## Project Description

This is a platform that controls a Super Monkey Ball-like game. With this platform, you tilt it in order to move a marble within a game. Your goal is to collect the cubes, while trying not to fall off the platform. However, the game will also interact with you; namely, when you collide with walls, the platform will jerk back and provide haptic feedback to the player, making this platform much more immersive.

This project uses the Novint Falcon as a base for the platform; The Novint Falcon was a haptic device that was around in the early 2000s that used three motors and potentiometers; When you tilt the platform, it tilts these potentiometers and moves the ball at the bottom of the platform, which sends it's position to the computer as mouse data. The platform itself is connected to the Falcon by three holders that are connected to the potentiometers of the platform, making it so when you tilt the platform, you also move the mouse.

On the software side, we communicate with Unity through a combination of drivers for the Novint Falcon written in C and a C# Unity script. When the Unity Scene starts, it starts up a C program that allows the Falcon to control the mouse. The Unity scene uses the mouse to control the ball.  The C# script then sends force-feedback data to the C driver by writing to its standard input, and the driver handles timing and applying the actual forces.

## Team Members

Chance Roberts (Hardware & Some Software/Hardware Integration)

Peter Gutenko (Software & Software/Hardware Integration)

## Resources

* PC/Mac with Unity
* The Unity scene found [here](https://www.github.com/pgutenko/falconball)
* The Novint Falcon
* Three 3D Printed Parts [(Seen here)](https://drive.google.com/file/d/17SCNblyjmt6xiE_PzqIuWfQsTN8A_lu0/view?usp=sharing)
* A Simple Foam Platform (Or a 3D Printed One)
* Various Pieces from the VEX Metal & Hardware Kit

## See People Trying it Out!

<iframe src="https://drive.google.com/file/d/1CHRlzGBlbZ6K87bdb7DcS2Jgntb00ShS/preview" width="640" height="480"></iframe>

(If that doesn't work, click [this](https://drive.google.com/file/d/1sGxxnrIiRAtWLJpJQj57ZGTuIsVGa0KO/view?usp=sharing)! )

<iframe src="https://drive.google.com/file/d/1h2AkBnbCdRst4vctfDhattXeIHwpTmFW/preview" width="640" height="480"></iframe>

(If that doesn't work, click [this](https://drive.google.com/file/d/1h2AkBnbCdRst4vctfDhattXeIHwpTmFW/view)!)

<iframe src="https://drive.google.com/file/d/1sGxxnrIiRAtWLJpJQj57ZGTuIsVGa0KO/preview" width="640" height="480"></iframe>

(If that doesn't work, click [this](https://drive.google.com/file/d/1CHRlzGBlbZ6K87bdb7DcS2Jgntb00ShS/view?))
