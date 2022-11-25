# Lane-Segmentation-for-Self-Driving-Cars

The purpose of this project is to develop a program that is able to detect lane lines on the road using computer vision techniques.  
It is much cheaper to equip a car with a front-facing camera than using techniques such as RADAR or LiDAR. Once we get an image from the camera, we process it using techniques such as Canny Edge detection and Hough Transform to detect the lane lines in the image and output the result.  
While this logic will work well for most situations, it is not perfect. It can fail when camera image is poor quality — as in case of poor lighting or if lane lines are not visible — presence of snow or debris on the road or if the roads are wavy or S shaped.
