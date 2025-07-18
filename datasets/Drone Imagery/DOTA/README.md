Dataset can be downloaded from https://captain-whu.github.io/DOTA/dataset.html

Data can be downloaded in parts of v1/1.5 and v2. V2 has updated labels for all previous images. To use, download all v1/1.5/2 images and all updated labels from v2. 

Labels are in the form of x1, y1, x2, y2, x3, y3, x4, y4, category, difficult, where the vertices are given in clockwise ordered pairs and difficult is a boolean value indicating whether a label is difficult. The labels will have to be programmatically rewritten for YOLO training. For YOLO directory structure and yaml example see xView dataset.   