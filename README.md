# Novel-MSB-Steganography
This repository entails an MSB steganography method for hiding text inside images with very little modification of the image. We use a special encoding technique to achieve this.


## Requirements:

This code uses Python 3.x.

The code operates on conent stored in your google drive. If you need you could simply change the paths in the appropriate ares of code and run it locally. If you want to run it as is, please make a folder in your google drive named stego and cover, out, secret as sub-directories. The cover image is to be placed in cover sub-directory.

## Example Input, Output Images
### Input:
<figure>
  <img src="https://github.com/G-360/Novel-MSB-Steganography/blob/db7d05d238009781fc0bd441350c2a0ddae45333/example%20io/stego_in.jpg" alt="Input Image">
  <figcaption>Input image 3 channel</figcaption>
</figure>

### Output:
<figure>
  <img src="https://github.com/G-360/Novel-MSB-Steganography/blob/db7d05d238009781fc0bd441350c2a0ddae45333/example%20io/stego_out.png" alt="Output Image">
  <figcaption>Output image with MSB encoding and minimal LSB modification</figcaption>
</figure>
