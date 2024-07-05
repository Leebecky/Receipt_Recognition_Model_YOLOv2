# RECEIPT RECOGNITION MODEL

- Download pretrained weights [here](https://pjreddie.com/media/files/yolov2.weights). Place this weights file in notebook directory and name it `yolo.weights`

_Please refer to the "jmpap Original README.md" for the complete rundown of this model._

## Acknowledgements
- This model uses the YOLOV2-Tensorflow-2.0 implementation done by <a href="https://github.com/jmpap/YOLOV2-Tensorflow-2.0/tree/master">jmpap</a>

- The model was retrained using the Receipt Database from <a href="https://expressexpense.com/blog/free-receipt-images-ocr-machine-learning-dataset/">ExpressExpense</a>

- All images in the dataset was resized using italojs' <a href="https://github.com/italojs/resize_dataset_pascalvoc">resize_dataset_pascalvoc</a>

- The anchors were calculated using K-Means as explained by <a href="https://fairyonice.github.io/Part_1_Object_Detection_with_Yolo_for_VOC_2014_data_anchor_box_clustering.html">Yumi's Blog</a>

Major thanks to all the authors of the projects that allowed me to complete this model.

_This model was done as part of the Object Detection & Localization Fundamentals Bootcamp by AI Nusantara x Krenovator._