# Detecting Barack Obama using Transfer Learning

There are two main approaches to Transfer Learning:

* Develop Model Approach
* Pre-trained Model Approach

Here, the pre-trained model approach is being followed. The aim of this project is to used an 'SSD MobileNet V1' model, pre-trained on the COCO dataset to detect Barack Obama in images.

---

The main steps followed were:

1. Prepared the directory. Created separate folders for the model, training/testing images, annotations, etc.

```
TensorFlow
├───scripts
│   └───preprocessing
└───workspace
    └───training_demo
        ├───annotations
        ├───exported-models
        ├───images
        │   ├───test
        │   └───train
        ├───models
        └───pre-trained-models
```

2. Selected the appropriate model. 

3. Added the label_map.pbtxt file to name the classes. 

4. Added the train and test images to the directory.

5. Added the generate_tfrecords.py file to generate record files for the images.

6. Installed necessary libraries.

7. Configured the pipeline according to my requirements.

8. Setup TensorBoard.

9. Trained the model.

10. Analyzed the results using tensor board.

![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/4e8f8f7aeff8c797ceb9aec11606a274/image.png)
![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/4e8f8f7aeff8c797ceb9aec11606a274/image.png)
![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/1d9eb990004cb3b2b07d8a522eb5dd63/image.png)

11. Exported the trained model.

12. Loaded the saved model and label_map.pbtxt file to test the working on new images. Following were the inferences:

![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/14840064be1069e1706027e2620ce770/image.png)
![image](https://gitlab.iotiot.in/newbies/ai-skilling/ai-e2e/model-training-/transfer-leaning-v2/uploads/e33c6b822b01c9a682937d764d61fae2/image.png)

---

**Link for the collab:** [Detecting Barack Obama](https://colab.research.google.com/drive/1_ofXIXRSFgY9qCdwgbNFbjlzRB4LIarM?usp=sharing)
