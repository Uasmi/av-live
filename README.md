# A/V Live Show Example


## Early-on
This was the first example of using Neural Network to generate image sequence reacting to music:
https://drive.google.com/open?id=13SLhO2HKRK7F_yK190q0R-xiwj1kgPT0

Other repos with code:
1. Freezing Models: https://github.com/Uasmi/model-utilities
2. Generating images on-the-go vs in advance: https://github.com/Uasmi/running-models
2. RMS (tracking music and visualizing with open-cv): https://github.com/Uasmi/simple-rms-python

## Setting things up
You need to have Max/MSP installed to run this patch. Simply copy the content from patch.txt and paste it to Max

You'll also need to use some pre-built neural nets to train your models and generate sources for the patch, for example the Nvidia PGGAN: https://github.com/tkarras/progressive_growing_of_gans 

## Current state of the project
This is a main Max/MSP patch which handles the 3D displacement and music tracking (included in this repo):
![](https://githubpics.blob.core.windows.net/av-live/patch.png)

Examples of generated visuals through 3D Displacement:
![](https://githubpics.blob.core.windows.net/av-live/example1.png)
![](https://githubpics.blob.core.windows.net/av-live/example2.png)

## Performance 
Acoustic Treatment Live: https://youtu.be/3Sfcw5JVPy8
Sample video: 
