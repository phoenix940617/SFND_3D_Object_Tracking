Attention: 
1 I have run my project in udacity workspace rightly again.(1 mkdir build, 2 cd build 3 cmake .. 4 make)
Please check the screenshots and a short-video of my work in MyResults file, which the last reviewer told me.

2 Accoring to the core-dump from reviewer, I have searched it on the internet(link: https://github.com/opencv/opencv/issues/15502) and been informed that the yolov3.weights file should be replaced.Then I got new one from link https://pjreddie.com/media/files/yolov3.weights and compressed it to yolov3.weights.tar.gz in dat/yolo file.Because of the limits of the environment, I can not verify it whether my project works or not in my udacity workspace. I really hope this change can work and I'm sure the problem is relevant to the core dump. 

I have submitted my projects so many times(about more than 3) just for the fault I did not met. I have tried my best to show my results.There are some thoughts in every step
  

TASK FP.1 : matchBoundingBoxes() function complished by which boundingboxes keypoints match pair are enclosed in the previous and the current time.
TASK FP.2 : computeTTCLidar() function complished by step1: filter the outliers who own the number of neighbour less than threshold; step2: compute the distance between the nearest inlier points  in the previous and the current time.stpe3:compute lidar-based TTC by distance in step2 and frameRate.  
TASK FP.3 : clusterKptMatchesWithROI() funciton complished by step1:look for the keypoints enclosed by the current boundingbox and record the corresponding match pair;step2:filter the points whose distance is larger than the threshold in the previous and current frame and get match pair whose corresponding points are in the current boundingbox.
TASK FP.4 : computeTTCCamera() function complished by the median ratio of relative distances in the previous and the current frame in case of outliers.
