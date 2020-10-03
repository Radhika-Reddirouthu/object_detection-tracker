This is a simple code that takes the live streaming video that is captured using phone camera as input and as per user's choice it can do any of the below options
1. object detection
2. object tracking
3. both object detection and tracking

To capture the live streaming video in phone and send it to laptop, "IP Webcam" app is used which is available in playstore.
Both laptop and mobile phone should be connected to the same wifi connection.

Follow the below steps to get started:
1. Download "frozen_inference_graph.pb" and "mscoco_label_map.pbtxt" or use your own trained model.
   I have downloaded it from the below mentioned links
   
   https://github.com/datitran/object_detector_app/blob/master/object_detection/ssd_mobilenet_v1_coco_11_06_2017/frozen_inference_graph.pb
   
   https://github.com/datitran/object_detector_app/blob/master/object_detection/data/mscoco_label_map.pbtxt
   
2. Open the "IP Webcam" app in the mobile and click on "Start server (Begin serving video stream)" option in the app. 
3. Provide the ip address shown in the app, where ever commented in the code.
4. Follow the comments written in the file and run all the cells in the jupyter notebook making the changes where ever required

I have taken the below mentioned blog as reference to write the code for object detection

https://nanonets.com/blog/real-time-object-detection-for-drones/

Thankyou  to the blog for providing clear explanation




