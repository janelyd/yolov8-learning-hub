# YOLOv8 
Common steps for all four topics in colab

```
from google.colab import drive
drive.mount("/content/drive")
```


1. image classification  --
  * -- model used : yolov8l-cls.pt
  * -- dataset : any pics from google images using extension
3. object detection      --
  *  -- model used : yolov8n.pt
 *  -- dataset : https://universe.roboflow.com/test-svk7h/brain-tumors-detection/dataset/2
4. object tracking       --
*   -- model used : yolo track model=yolov8n.pt
  * -- dataset : any video from pixabay
5. image segmentation    --
 *  -- model used : yolo segment predict model=yolov8x-seg.pt
  * -- dataset : https://universe.roboflow.com/project-p5nyc/car-parts-o7dlr
6. keypoint detection
  * -- model used : yolo pose predict model=yolov8n-pose.pt
  * -- dataset : i used naim suleymanoglu for posing. you choose yours.
 


  ## Steps & Tools
   * Fatkun Batch or any other image downloader extension from google images
   * Preparing the dataset
   * Rename and split the dataset (splitting as train 80 validation 10 test 10)
   * Labeling them in Roboflow ( or get the labeled dataset all from Roboflow)
   * choose the correct model and train the data
