# Object-Detection-using-TensorFlow-API
Built a 6 class object detection model using Tensorflow API with Faster-RCNN-Inception-V2-COCO model from TensorFlow's model zoo. Due to the limitation of computing power this project was completed on a Tensorflow CPU version.

Tensorflow object detection repository was downloaded from  https://github.com/tensorflow/models

The TFRecords that serve as input data to the TensorFlow training model. In this uses the xml_to_csv.py and generate_tfrecord.py scripts from Dat Tran’s Raccoon Detector dataset, with some slight modifications to work with my directory structure.

And for labeling used LabelImg (https://github.com/tzutalin/labelImg)

Create a pipline to setup Tensorflow API 

In case of quuestion or doubts reach out to rudrarajurahul@gmail.com

# About Dataset
Selected 6 object available in my house and clicked images from my phone of all the objects 40 each and then overlapping with each other and other objects as well. Collected a total of 280 images and split it into 80:20 ratio for train and test.

# Target Object 
1. Apple TV Remote
2. Instax Camera
3. Instax Printer
4. Esp8266
5. Flower Pot
6. Adaptor

# System Specification 
- Tensorflow: 1.15.0
- OS : MacOS

# Steps followed 

1. Directory Setup on local drive
2. Create Virtual Environment	on pycharm
3. Setting up Object Detection Directory Structure	
4. Setting Up Virtual Environment	
5. Install COCI API	
6. Setup environment variables & Build and Install setup.py	
7. Compile Protobufs	
8. Testing TensorFlow Object Detection API	
9. Gathering Data	
10. Labeling Data	
11. Generating xml to csv  files	
12. Generating TFR Records	
13. Creating Label Map	
14. Configuring Training	
15. Setting up tensor board	
16. Training Model	
17. Converting saved model to TensorFlow [ inference graph]	
18. Find the .pb file in the inference_graph directory	
19. Testing the trained model	

# Output

![Detection Output](https://github.com/rudrarajurahul/Object-Detection-using-TensorFlow-API/blob/master/Screenshot%202020-05-11%20at%209.42.20%20PM.png)

![Detection Output 2](https://github.com/rudrarajurahul/Object-Detection-using-TensorFlow-API/blob/master/Screenshot%202020-05-11%20at%209.48.06%20PM.png)

![Detection Output 3](https://github.com/rudrarajurahul/Object-Detection-using-TensorFlow-API/blob/master/Screenshot%202020-05-11%20at%209.50.53%20PM.png)

# Source Credit
1. EdjeElectronics (https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10)
2. Dat Tran (https://github.com/datitran/raccoon_dataset)
3. Adria Gil (https://towardsdatascience.com/training-tensorflow-object-detection-api-with-custom-dataset-for-working-in-javascript-and-vue-js-6634e0f33e03)
