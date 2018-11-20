# Project: Can you unscramble a blurry image? 
![image](figs/example.png)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2018

+ Team 6
+ **Team members**:
	+ Izzy Beers 
	+ YenHsiang Chen 
	+ Yimeng Qiu 
	+ Binhan Wang 
	+ Yaxin Wang 

+ **Project summary**: In this project, we created a baseline model to generate predicted high resolution images from original low resolution images. Then, we tried to use Convolutional Neural Network to improve the performance of our existing model. For the Baseline model, we got 25.6 for average PSNR score, after train the SRCNN model, we got the final 34.8 PSNR score.
	
**Contribution statement**:

+ Izzy Beers: created initial versions of functions being called
+ YenHsiang Chen: improved `feature` and created `superResolution`
+ Yimeng Qiu: designed and created the CNN improved model 
+ Binhan Wang: tuned the paramters, trained the model for baseline 
+ Yaxin Wang: extracted the features from training images.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
