# image-mods
Simple program to perform various modifications to images. This was done for practice and everything here can surely be done in any major photo editing software in superior terms.

## Usage
Run the program in a terminal as you would any python file.
  
> username@desktop:~$ python main.py -flag  

Images are saved to same folder as program with the format 'original_filename_filter.png'.
Large images may take some time to process.  
<p> To see what images may look like, go to the 'previews' folder.  
  
[cImage.py](https://github.com/bnmnetp/cImage) is a library not written by me, it is included for usability.

### Possible flags are as follows:

[-n] [--negative] - Returns negative version of input image.

[-nr] [--nored] - Returns input image with no red.

[-ore] [--onlyred] - Returns input image with only red.

[-ng] [--nogreen] - Returns input image with no green.

[-og] [--onlygreen] - Returns input image with only green.

[-nb] [--noblue] - Returns input image with no blue.

[-ob] [--onlyblue] - Returns input image with only blue.

[-g] [--grayscale] - Returns input image as grayscale.

[-bw] [--blackwhite] - Returns input image as black and white (literally just black and white).

[-s] [--sepia] - Returns input image with sepia tone.

[-db] [--deblock] - Returns input image with blocking reduced.

[-db] [--denoise] - Returns input image with noise reduced.

[-rgb] [--rgbtint] - Returns input image with RGB tint, one for each third of image.

[-bow] [--rainbow] - Returns input image with rainbow filter.

[-b] [--brighten] - Returns input image with brightness increased by specified factor.

[-df] [--deepfry] - Returns a 'deep-fried' version of the input image.


 






