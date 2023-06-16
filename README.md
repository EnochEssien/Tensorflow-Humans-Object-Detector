# Summary 

The Tensorflow Object Detection API is a powerful tool that allows developers to create accurate and efficient object detection models. In this case, a specific implementation of the API has been utilized to develop an object detector capable of detecting humans in an image.

## Installation

If one is trying to run the detection script and test the object detector then no pre-installation is needed as long as suitatable python editor is available, though some additional Libraries and Dependancies would be needed, as seen below. 

As for instructions on training your own custom object detector, refer to this instructional video, https://www.youtube.com/watch?v=8ktcGQ-XreQ&t=2731s&pp=ygUldGVuc29yZmxvdyBvYmplY3QgZGV0ZWN0aW9uIGxhenkgdGVjaA%3D%3D

And the dataset used to train this particular object detector, https://www.kaggle.com/datasets/constantinwerner/human-detection-dataset 
found from kaggle


## Libraries and Dependancies
If version isn't specified, install the latest update
All these libraries can all be installed using the "Pip" command

1. Python 
2. Tensorflow
3. Protobuf
4. Tensorflow-Object-Detection-api
5. OpenCV
6. tf_slim


## How to use 

To run the Object Detection Script, all you'd have to do is simply download this repository, and edit the PATHs in the script, 

***PipelinePATH*** : this points to the "pipeline.config" file seen in the folder in this project

***ModelPATH*** : this points to the model folder seen in this project, the "saved_model" folder seen in the "HumanDetectorV1" folder

***LabelMapPATH*** : this points to the text file containing the classes of the detector seen in the folder in this project, "Humans_label_map.pbtxt"

***TestVideoPATH*** : this points to the video of you choice that would be used to test the object detector


## Example Output

![image](https://github.com/EnochEssien/Tensorflow-Humans-Object-Detector/assets/91120304/3c951939-3c2b-4c1d-a302-dcbc499c0790)



