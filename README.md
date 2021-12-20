# Traffic-CONTROL-System---MATLAB
A traffic control system which counts the number of vehicles and detects passage of any emergency vehicle. 
This will help in dynamic traffic signal system which will lead to an efficient passage of traffic.
#
The CODE is entirely written in MATLAB.
#
FILES : 
Vehicle_count.m       : This is a merging of all the other files. You can RUN this file alone to get the intermediate as well as the final results.
                        When we run this, intermediate files(mp4/avi) will be generated (refer flowchart in report) and frame by frame counting is done.
traffic3              : This is the input video file
ambulence_detect_image: Detect ambulance in video frame
rgb_to_gray           : Video file frame from rgb to gray
bg_sub_approxmedian   : Background Subtraction of Edge Video
bg_sub_offline_mean   : Background Subtraction of Gray Video
edge_detect           : Edge detection using sobel/canny filter
thresholding          : Thresholding to get  object of interst
morpho                : Convolution/Erosion/Dilation

#
all other files should be RUN in a particular order which generates an output which the other file uses as INPUT.
Presentation and final report uploaded
