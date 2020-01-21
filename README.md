# image-selector-opencv-python

This program has been designed for use in a machine learning - data science context; with the objective of speeding up image selection.

The program is designed to read images from a video and resizes the original images down into a grid, allowing 
the user to select a span of images and tag the images with text. A text file containing the frame numbers and tagging 
is produced on each press of the space bar; The next lot of images are also fed into the grid on Space bar.

Keyboard and mouse shortcuts:
```
Esc = Exit the program.
Left mouse click = Select span of images.
Right mouse click = Undo image span selection.
Space bar = Go to next set of images and store tagged images + frame numbers in text file.
```

```Example of program in use with images selected and entering a tag for image span```
![Screenshot](https://github.com/LeeWannacott/image-selector-opencv-python/blob/master/Example_of_use.png)

```Text file with list of tags and corresponding frame numbers produced on each Space bar```
![Screenshot](https://github.com/LeeWannacott/image-selector-opencv-python/blob/master/List_of_images.png)
