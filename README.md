
This is some of the MNIST database of 28x28 pixel handwritten digits.
I took 13010 samples from this database, or 1301 images for each digit,
and I wrote them to a binary file with no header, just data. 4 Bytes per
float, in Big Endian, all values between 0 and 1 inclusive. 
The images are laid out row by row as follows:

0 .25 .5  .75 1
0 .5  .5  1   1
0 .33 .33 .66 1

Turns into:

0 .25 .5 .75 1 0 .5 .5 1 1 0 .33 .33 .66 1