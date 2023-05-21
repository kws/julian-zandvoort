# Video overlays

If you attend Bleekemolen's Race Planet you have the option of having your laps recorded. The SD card comes with the video streams and software to extract the GPS data. I have previously written projects to extract the data, but since the software already did this, I didn't bother for this project. 

I wanted to add our own video overlays, so this project provides three small jupyter notebooks:

1. [combine-data.ipynb](./notebooks/combine-data.ipynb) - Combine the GPS data for each video segment

2. [speed_gauge.ipynb](./notebooks/speed_gauge.ipynb) - Create a speed gauge

3. [map.ipynb](./notebooks/map.ipynb) - Plots the current possition on the track map.

## Installation

The dependencies can be found in pyproject.toml - you can use a tool such as Poetry to set up an environment.

## Map

The map files may be subject to copyright, so I'm not including those here. However, for our video (only for personal use) I used the F1 track layout:

![F1 track layout](https://media.formula1.com/image/upload/content/dam/fom-website/2018-redesign-assets/Circuit%20maps%2016x9/Netherlands_Circuit.png.transform/9col/image.png)

If you use a different image, you will have to adjust the projection coordinates in the notebook accordingly.