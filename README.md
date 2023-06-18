# Car-Brand-Detection

## Description

Car detection and recognition is one of the most important research contents, and it is also crucial to the safe driving of cars. Real-time detection and recognition of current cars can effectively prevent the occurrence of malignant traffic accidents such as rear-end collision. The difficulties like occlusion, lighting, and object shape changes can be solved using car detection.In this project I created a  Car Brand Detection System which will detect the car brand by taking essential input image. The model is build using Resnet50.The frond of this project created using html,css and for backend flask is used.
 
 
 
 
![Screenshot_20230618_023638](https://github.com/HajaraCM/Car-Brand-Detection-Using-Deep-Learning/assets/117503246/861ed95f-0148-41fd-b513-62bb752d89ce)
![Screenshot_20230618_023752](https://github.com/HajaraCM/Car-Brand-Detection-Using-Deep-Learning/assets/117503246/587784b8-43f6-4b69-808b-734e1fb12d8a)

 
 
## Technical Process

Following are the technologies that are used to develop the project.

* **Front-end development**: HTML,CSS.
* **Back-end development**: Flask,Deeplearning,Transfer Learning.

## Functionality

System will read the image uploaded by the user, augment it and will use the saved custom model to detect car brand and thus display the result in a user-friendly language.

**Below are the steps**:
 
  * **Upload image**: 
  
    The user can upload the car brand image through a workstation running on Windows OS.The image should be in jpeg, png or jpg format.
       
  * **Read Image**:
  
    The image will be scanned before augmentation takes place.
      
  * **Transform Image**
  
    The scanned image is then transformed into a format that is needed by the saved custom model.
      
  * **Evaluate image using saved model**:
  
    The saved custom model creates a feature map of the uploaded car brand image and predicts the output.
      
  * **Determine and Analyze the Output**:
  
    The predicted output is then analyzed and converted to a user friendly language.
      
  * **Display the Output**:
  
    The analyzed result is then displayed to the user.


## Assumptions and Dependencies
If the user has a workstation that works on Windows OS then that person can easily use the predicting interface. The user also has to have the car brand images in JPEG, JPG or PNG format for prediction purpose.

## Product Requirements

**Operating Environment**

  * **Operating System***: Minimum Windows XP or Windows VISTA. Better environment Windows 7, 8, 8.1, 10.
  * **Language**: Python 3.6 or Python 3.7
  * A workstation which will run on any Windows OS is needed to predict the diseases using this system.
  
**Performance Requirements**

  * The product performance will be based on a local system.
  * The image prediction will take some time.
  * The evaluation performance will depend on some software and hardware components.
