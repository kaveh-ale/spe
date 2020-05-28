# Project

ALE Python Examples
Developed by Kaveh Majidi @ ALE
An Example on how to use Python and saa on ALE AOS
In this example, saa will ping a specific IP address and on failure of the ping it will execute the python script called check-camera.py on the switch. The python script will admin disable/Enable the POE port that the camera is connected.
Use case is that some cameras will go into sleep after a period of inactivity. To bring them up again you need to disable/enable the POE port.

# Version

1.0

# Requirements

Python > 3.2

# How to use
Modify the port-map.txt file to reflect the ports that are connected to cameras.
Copy the check-camera.py  and port-map.txt to the python directory of the switch.(/flash/python)
Use the sample-switch-config.txt file as an example how to configure saa on the Switch
After starting the saa, monitor the switch for execution of the script. Minimum interval for saa check is 1 minute. Refer to saa documentation for further configuration options.


# Dependencies
N/A

# License

This project is licensed under the MIT License

Copyright (c) [2020] [Kaveh Majidi]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
