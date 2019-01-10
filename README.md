# webcam_point_features
Exercise 2.1 of the Perception Systems course. Detection of ORB features from online webcam images.


We start the exercise bu forking the git repository https://github.com/beta-robots/webcam_point_features, cloning it to out computer with the command

    $  git clone https://github.com/EloiSoldevilaDalmau/webcam_point_features
  
and building the point_capture example.

To build it we create a directory called "build" inside the webcam_point_features directory (

    $ mkdir build
) and, being inside the new directory compiling it cmake files. First with 

    $ cmake .. 
and then 

    $ make 

To execute the example we write 

    $ ./point_features 
when inside the build directory.


The following image is an example of what can be seen using it.

<img src="images/webcam_point_features.png" width="500">
    

