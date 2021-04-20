# Change-Background
this pipeline uses hrnet for creating segmentation masks of the person and then crop that image according to the mask, then it keeps the cropped image over the background image provided. As evident the programs requires two input in case of a background change. You can also leave the second image, in this case pipeline works as a background removal code.

## Running script

### Weights

Download weights from here:

https://drive.google.com/file/d/1VNYZ1X5bnIZFIVIgNi9JwqCNIvioxexe/view?usp=sharing

### Run 

``` python main.py --image --bg_image --weights --debug --output_dir ```


### Input 

<img src="https://github.com/theAyushAT/Background-Change/blob/main/demo_images/background.jpg" width="320.0" height= "213.3"> <img src= "https://github.com/theAyushAT/Background-Change/blob/main/demo_images/image1.jpg" width= "325" height= "487.5">


## Output
<img src="https://github.com/theAyushAT/Background-Change/blob/main/demo_images/final1.png" width= "325" height= "487.5">





