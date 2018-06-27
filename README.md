# LabelMeFacade

Data created September/3/2010

Authors: Bjoern Froehlich and Erik Rodner

## What is this?

A GUI program to help users quickly label unconstrained photographs of city scenes, like this:

![Alt text](./images/05june05_static_street_boston__p1010736.jpg?raw=true "Raw unconstrained photograph")



Labelled by human hands using the LabelMe tool thustly:

![Alt text](./labels/05june05_static_street_boston__p1010736.png?raw=true "label for previous image")

You could use this labelled image data to train a machine learning algorithm to find windows, buildings, roads, cars, shrubberies, etc.

# Label classification color legend:

The dataset under images/ contains 100 images for training and 845 images for testing (see train.txt and test.txt for details).  Color codes for labels are (in R:G:B):

    various = 0:0:0
    building = 128:0:0
    car = 128:0:128
    door = 128:128:0
    pavement = 128:128:128
    road = 128:64:0
    sky = 0:128:128
    vegetation = 0:128:0
    window = 0:0:128

# Explanation

This is the LabelMeFacade Image Dataset, which we created from LabelMe images for semantic segmentation research. Since this is a subset of LabelMe images, the images were originally collected by the authors of

LabelMe: A Database and Web-based Tool for Image Annotation Bryan C. Russell, Antonio Torralba, Kevin P. Murphy,William T. Freeman:
http://publications.csail.mit.edu/tmp/MIT-CSAIL-TR-2005-056.pdf . 

All images should only be used for non-commercial and research experiments. Please check with the authors of the LabelMe dataset, in case you are unsure about the respective copyrights and how they apply.


## Citation

If you use this database please cite one of the following papers:

    @INPROCEEDINGS{Froehlich-Rodner-Denzler-ICPR2010,
	    author = {Bj{\"o}rn Fr{\"o}hlich and Erik Rodner and Joachim Denzler},
    	title = {A Fast Approach for Pixelwise Labeling of Facade Images},
	    booktitle = {Proceedings of the International Conference on Pattern Recognition
    	(ICPR 2010)},
    	year = {2010},
    }

    @inproceedings{Brust15:ECP,
        author = {Clemens-Alexander Brust and Sven Sickert and Marcel Simon and Erik Rodner and Joachim Denzler},
        booktitle = {CVPR Workshop on Scene Understanding (CVPR-WS)},
        title = {Efficient Convolutional Patch Networks for Scene Understanding},
        year = {2015},
    }

