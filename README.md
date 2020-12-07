# GSpy_glitch_classification

## About the project

Final Project for DATS 6202 Machine Learning I at GWU taught by Professor Yuxiao Huang. The goal was to apply various machine learning algorithms using real-world data. 

## About the data

The original data was found <a href="https://www.kaggle.com/tentotheminus9/gravity-spy-gravitational-waves">here on Kaggle</a>, and contains three folders (with subfolders) of images for training, testing, and validation. There are 22 subfolders which organize the images into their glitch categories, which are 

* 1080 lines
* 1400 ripples
* air compressor
* blip
* chirp
* extremely loud
* helix
* koi fish
* light modulation
* low frequency burst
* low frequency lines
* no glitch
* none of the above
* paired doves
* power line
* repeating blips
* scattered light
* scratchy
* tomte
* violin mode
* wandering line
* whistle

Each glitch has 4 associated images, where the time range is decreased and decreased to get a zoomed in image of the glitch, so if there are 16 images in a glitch folder, there are "actually" 4 unqiue glitches. However, the images in this data set are only the plot space - axis labels, tick marks, legend, title, essentially anything extraneous - has been removed. There are 22349 images in the testing dataset, 4733 images in the training dataset, and 4800 images in the validation dataset.
