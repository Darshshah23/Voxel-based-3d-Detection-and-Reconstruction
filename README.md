Object detection from Image:

1) Open Google colab 
2) upload object_detection file in google colab
3) After opening the object_detection file, go the the file
   icon on the left and drag and drop the following files into that:
	1) coco.name
	2) yolov3.cfg
	3) yolov3. weights (Download the weights from https://www.kaggle.com/datasets/shivam316/yolov3-weights)
	4) Images
4) Now run each cells one by one
5) First install Mediapipe, then import Library, After that load YOLO,
   make list of classes and load Network. Then run the define function and at the
   end load and read an image in which you want to detect.
6) you will get the output.

Now for 3d bouding box:

1)Run the cell for loading the image
2)Now run the cell to create Bounding Box around the object


live Object detection:

1)Open yolo.py and run the code 
 
 For 3D reconstruction:
 1. open the google codab lin provided following or open the 3D Reconstruction.ipynb file provided in the folder. 
 https://colab.research.google.com/drive/1Soz2y6siPBn9r5JdQGLztQahDteq7EPS?usp=sharing
 2. follow the step by step instruction provided inside.
 3. make sure to upload the image from the folder called "human" from the above(10 images are there).
 4. use blander tool to view the 3D model of the reconstructed image.
 the link to downlaod latest blender software is: https://www.blender.org/download/
