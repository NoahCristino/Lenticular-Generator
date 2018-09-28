# Lenticular-Generator
Generates Lenticular Images
# Vocab
I have no clue if some of these words in the documention really exist but here's what I mean
* Lenticular - something made with lenticular printing
* Lenticulite - a strip on the image (ridges)
*I don't know if it is lenticulatite or lenticulation since they both sound the same and google doesn't help*
# Prerequisites
* [Python 3](https://www.python.org/downloads/)
* [Pillow](https://pillow.readthedocs.io/en/5.2.x/)
# Running
1) Download this repository and install all of the prerequisites above.
2) Get 2 images which you want to use, make sure they are the same exact size
3) Choose the amount of lenticules
    * If you are trying to print it more lenticules = better quality, but the more you have the harder it will be to fold (16 is recommended if you print it taking up the whole page in landscape mode).
    * If you just want to create a cool design where you can see both images at the same time try to set it to the width of the images in pixels
4) Run the program `python lenticulation.py image1.png image2.png lenticules` replace `image1.png` and `image2.png` with your images and `lenticules` with the amount of lenticules
# Printing
1) Print out the generated image, and cut it out
2) Fold along each lenticulite like this:
![Folded Paper](http://sydneys18.weebly.com/uploads/2/5/8/9/25894045/9463040_orig.jpg)
3) Now tilt the paper and you should be able to see both pictures depending on where you look
# Examples
![Final](http://freegifmaker.me/img/res/1/5/3/8/1/6/153816171968569.gif?1538161729)
