# One Shot II
This paper quote from https://github.com/affinelayer/pix2pix-tensorflow .

Based on pix2pix by Isola et al

## Setup

### Prerequisites
  Tensorflow 1.4.1 or higher
  
### Recommended
  Windows with Tensorflow GPU edition + cuDNN
  
## Datasets and Trained Models
The data format used by this program is the same as the original pix2pix format, which consists of images of input and desired output side by side. 

## Training
Use PIX2PIX GAN automatically train 50 different illumination template.

## Testing
The testing mode will load some of the configuration options from the checkpoint provided.

## Taget object image 
Use "Take Picture" to take one image of taget object.

## Generating illumination effect on target object image
Using test in Pix2Pix GAN to generate 50 different illumination effect on image of taget object.

## Object coordinate detector training 
Gather all generated image and original image inside a folder and use "PDT" for object coordinate detector training.

## Object coordinate detector test
Use "Detection" for Object coordinate detector test
