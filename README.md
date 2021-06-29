# WCamTimeLapse
A simple program to help you make time lapse video clips with your webcam.

WCamTimeLapse is a tool to help your make simple time lapse clips with your webcam.
Its pretty much a big hack of webcam sample code I found on different sites.

- No installation required.
- Only requirement is that you have .net installed (ver 2.0 or newer).
- Work in Windows XP (sp2) and Vista.
- Coded in C#

![b7e201c6-6858-42ef-82d0-82fce063307c](https://user-images.githubusercontent.com/74606519/123809520-f7244780-d8f1-11eb-8403-5cc429cf2d7e.jpg)

It's a pretty simple application. First you set the delay time between each picture, default is 1000 ms (1 sec), and then enter
the fps(Frames Per Second) your clip will be using 25, 10, etc (this value is used for the clip time calculation).
Click start to run, or check the Timed run: if you want to capture from a specific time to a another specific time, select the from and to time and then click start.

When you click the start button, a select dialog will pop op and ask you to select the folder where you want to save all the images.
This program will not make the video file for you, it will only taken the images, but you can use virtualdub (http://virtualdub.sourceforge.net/) to make it into a movie clip (see http://diy.wikia.com/wiki/Time_Lapse_Photography).

Limitations :
• The program is set to take pictures in 640x480, but it may vary, it depends on your webcam driver.
• I don't know how many webcams are supported, the two webcams I have, work, but I don't know if yours will.

Source code included.
