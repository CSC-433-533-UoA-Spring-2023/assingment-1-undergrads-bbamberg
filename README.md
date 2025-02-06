Author: Brendan Bamberg [uabbamberg@arizona.edu]  
Course: Undergrad 433
Date: [February]. [5th], 2025

**PLEASE UPDATE THIS README TO INCLUDE:**
* a text description of how to run your program, 
* document any idiosyncrasies, behaviors, or bugs of note that you want us to be aware of when grading, and
* any other comments that you feel are relevant.

Executing program:
Open the index.html file in a browser. Select the "Choose File" button and choose a ppm image file. The
image and final transformation matrix will automatically appear on the screen and the image will rotate.

Description:
This program processes a ppm image file and rotates it counter-clockwise using translation, scaling, and
rotation matrices. As the image rotates, it will also scale to ensure that clipping at the edges of the
image don't occur, which was done for bonus credit on top of the undergraduate requirements.

There are no known errors in this program.

Included files (**PLEASE ADD/UPDATE THIS LIST**):
* index.html    -- a sample html file with a canvas
* a01.js        -- a sample javascript file for functionality with the image uploading, and a method to parse PPM images
* Math.js		    -- some math functions that you can use and extend yourself
* bunny.ppm     -- a test image
* pic1.ppm      -- a second test image


**PLEASE PROVIDE ANY ATTRIBUTION HERE**
* Images obtained from the following sources:
  * bunny: http://graphics.stanford.edu/data/3Dscanrep/  
