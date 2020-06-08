# persciirender -> fork
I've forked and modified https://github.com/gnacu/petsciirender slightly. It now allows a file to be uploaded instead of having to modify the source, and I made it ever-so-slightly prettier to look at. I've also doubled the default size from 320x200 to 640x400, which is not canonical PETSCII but produces more detailed images, which is what I wanted.


# petsciirender
A web-based PETSCII Art Renderer

Load petscii_converter.html in a web browser. It will automatically render whatever was the last image name typed into the source code. Change the image specified by the source image tag near the bottom of the file to have it render a different image. 

The image does not need to be 320x200, it will be automatically scaled and resized to fit the 320x200 canvas. 

Safari 10 does not seem to want to save the file. However, the Safari Technology Preview does. You only need to save the file if you want to load it up on a real C64, or in an emulator. The .D64 file contains several prerendered and saved files. It also contains the BASIC program I wrote to render the .pet files to the C64's screen.

Enjoy.
