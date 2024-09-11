# Image Encryption
This repository contains a Python script that performs basic image encryption using two techniques: **random pixel swapping** and **adding a user-specified value** to the RGB channels of each pixel.

## Features

### 1. **Count Total Pixels**
   - This function calculates the total number of pixels in an image by multiplying the image’s width and height.

### 2. **Swap Pixels**
   - This method randomly swaps two pixels in the image for a number of iterations equal to the total number of pixels. The more pixels swapped, the more scrambled and obfuscated the image becomes.

### 3. **Add Value to Pixels**
   - This method adds a user-specified integer value to the RGB (Red, Green, Blue) channels of every pixel in the image. The values are modulated by 256 to ensure they remain within the valid range for pixel intensities (0-255), creating a color shift across the image.

### 4. **Encrypt Image**
   - Users can choose between the `swap` or `add value` methods to apply the encryption. After selecting the method and, if needed, providing an encryption value, the modified image is saved to a specified output path.

## How to Use

### Step 1: Setup

1. Clone or download the repository.
2. Ensure you have Python 3.x installed on your machine.
3. Install the required Python libraries:

   ```bash
   pip install pillow
