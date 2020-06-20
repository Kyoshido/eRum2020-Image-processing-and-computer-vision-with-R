# Image processing and computer vision with R

Materials depository for workshop "Image processing and computer vision with R" held at e-Rum 2020

http://2020.erum.io/program/workshops/

## Abstract 

Although R is sometimes not considered as a number-one language for image processing, there are options for effectively handling these tasks in the R environment. Furthermore, a large R speaking community would like to combine image data analysis with other kinds of analyses by keeping all their code "under one roof" within R.

In this workshop, we will revisit available packages such as magick, imager, EBImage (and some others) written purely in R (and for R), which deal mainly with image processing. A couple of times will be dedicated to amazing Bnosac’s family of R packages enabling computer vision and some other algorithmic tasks, besides other, objects or face detection and recognition. We will also take a short look a bit deeper into state-of-the-art possibilities bridging the R environment to non-R-based libraries using API packages, namely employing of dlib R package.

## First part of workhop by Lubomír Štěpánek
https://github.com/LStepanek/eRum_2020_image_processing_and_computer_vision_with_R/

## First part of workhop by Jiří Novák
In the second part of the workshop we explore package image.darknet by BNOSAC https://github.com/bnosac/image
where we show how to use this packkage for: 
* classification 

                label probability
1 Rhodesian ridgeback  0.31284952
2   Italian greyhound  0.17719932
3       Irish terrier  0.10811522
4          Weimaraner  0.06727524
5             redbone  0.06160372

* and detection of the objects in the image.
![Test Image 1](https://github.com/Kyoshido/workshop_e-Rum2020_darknet/blob/master/saved_predictions/dog_tv.png)


