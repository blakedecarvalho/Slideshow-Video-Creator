# Slideshow-Video-Creator
Bash script to make a video out of purely images

WHAT THIS SCRIPT IS FOR:
For people that want to generate a random video slideshow from a group of images. Very useful for quick visuals.

BEFORE USE:
-Make sure all images are in a singular format (such as all jpg or png).  Free software I recommend is Bulk Image Converter from sourceforge.
-Number all images numerically (examples: 1.jpg to 50000.jpg) which can be done using the free software Bulk Rename Utility
-Ignore warning text on first usage of executable.

HOW TO MODIFY:
Change the selection of images: In the script where it says $((RANDOM%18489948+1)), change the big number to the final image number (30000 if 300000.jpg) and 1 to whatever the first image number is.
Changing the numbers in "-framerate 1/.15" changes image speed.  Default is fast.
Change the final product name of "donezo" if you want.  Everytime you run it the last video will be deleted and replaced.

-For advanced modifications, such as linear organization, look at the ffmpeg docs which this shaped from

TO CREATE AN EXECUTEABLE VERSION (of a bash script) FOR NEWCOMERS:
1) cd to the location of choice,
2) open nano
3) input script
4) save
