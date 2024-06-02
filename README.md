# PRODIGY_CS_02
# Simple Image Encryption Tool

This is a simple Python tool for encrypting and decrypting images using basic pixel manipulation techniques. The tool allows users to either swap pixel values or apply a basic mathematical operation to each pixel for encryption and decryption.

## Features

- Encrypt images by manipulating pixel values.
- Decrypt images by reversing the manipulation process.
- Two modes of operation:
  - Pixel swapping
  - Mathematical operation (e.g., adding/subtracting a constant value to/from each pixel)

## Requirements

- Python 3.x
- PIL (Python Imaging Library, also known as Pillow)

## How It Works

# Pixel Swapping
Encryption: Swaps the values of pixels at specified intervals. For example, if the interval is 2, it swaps every second pixel with the next one.
Decryption: Reverses the swapping process using the same interval.

# Mathematical Operation
Encryption: Applies a mathematical operation (e.g., adding a constant value) to each pixel's RGB values.
Decryption: Reverses the operation (e.g., subtracting the same constant value) to retrieve the original pixel values.

## Output
![Screenshot 2024-06-02 204633](https://github.com/omaimajameel11/PRODIGY_CS_02/assets/167120544/846b326a-864c-4079-a7e7-cdef6c9c898d)

