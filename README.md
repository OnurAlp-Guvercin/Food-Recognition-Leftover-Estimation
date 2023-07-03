# Food-Recognition-Leftover-Estimation
This project presents a computer vision system for object detection, segmentation, and evaluation. 
The system starts by reading input files, specifically a folder containing the trays to be analyzed. 
The code automatically scans the folder, reads the images, mask images, and bounding box files, 
providing feedback on the code's functionality. Various detection techniques such as template matching, 
template matching with scale and rotation invariance, SIFT feature-based matching and segmentation 
techniques such as Thresholding, Region Growing, Watershed, and Grabcut were explored, with Grabcut 
being selected as the most suitable algorithm for accurate segmentation. We only provide template matching 
and Grabcut algorithms with the code. The Grabcut algorithm effectively differentiated between 
foreground and background objects, even in the presence of color similarities. The system's segmentation 
performance was evaluated using ground truth annotations, aligning the segmentation approach with the 
reference annotations and fine-tuning the algorithm for optimal alignment. The evaluation included metrics 
such as mean average precision (mAP) for detection, mean intersection over union (mIoU) for segmentation, 
and food leftover estimation. The results demonstrated the effectiveness of the traditional computer vision 
techniques in detecting, segmenting, and evaluating objects.
