# AsyncHTTPCaller
AsyncHTTPCaller is a FME Desktop transformer with key purpose to make HTTP requests asyncronized and fast.

To make this transformer compatible with your FME Desktop you need:

FME Desktop > build 18474

You need to install these addinional libraries in python 3.6:
aiohttp and it requirements
in this  folder:
..YourFMEHomeFolder\fmepython36

Check your install by importing aiohttp in PythonCaller, or PythonCreator or in any other places where you can use python in FME.

Next install this transformer by downloading AsyncHTTPCaller.fmx, doubleclick or rightclick and choose application to run this.

