# AsyncHTTPCaller
AsyncHTTPCaller is a FME Desktop transformer with key purpose to make HTTP requests asyncronized and fast.

To make this transformer compatible with your FME Desktop you need:

FME Desktop > build 19801

This transformer will install required packages aiohttp and aiofiles.
Install might fail, it will try to install these in servereal different ways.
If install fails it will fallback on request and do synchronus downloads.

Next install this transformer by downloading AsyncHTTPCaller.fmx, doubleclick or rightclick and choose application to run this.

