# LesionDetector
Detection of lesions using endoscopic imaging data.

We develop a lesion detection model using meditation data of Capsule Endascopy (capsule endoscope), which is used for minimally invasive surgery. 

Muti-Class Object Detection is performed and the number of classes is 4.

## [[LesionDetector results report🤩_Google Slides]](https://docs.google.com/presentation/d/1czDgY-yaeu8xQ2Nsb3zrnCk0k8tPcUC3Hf3JP6nbm-c/edit?usp=sharing)

## 01 Data set
1. train - 62,622 training JSON files.
2. test - 20,874 test JSON files.
#### *The image data is included in the JSON files in base64 format.

3. class_id.csv -  ID information for submission by object type.

<div align="center">
  
|Class (Object Name)| Class_ID (Object ID)|
| --------------- |----------:| 
| 01_ulcer      |1|
| 02_mass       |2| 
| 04_lymph      |3|
| 05_bleeding   |4|

</div>

### The images are decoded using the base64 method.
<p align="center"><img src ="https://github.com/hyeseon-cpu/Test/assets/128684012/fb59966b-5385-4f98-8bb1-da4d2cf91230" width="600"></p>

## 02 EDA

### Statistics by Lesion Type
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/3350cb43-559a-49f8-bc8f-e43fdc124974" width="600"></p>

### Cases with Only One Type of Lesion
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/2fe428fb-bf7f-488c-ae30-02c9c3f3d712" width="600"></p>

### Cases with Two Types of Lesions
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/e28a236e-1891-4fab-9970-731a67fdef48" width="600"></p>

### Cases with Duplicate Lesions
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/07d44d62-8118-4287-a9f0-c4d88ced9c55" width="600"></p>

### Image Size Statistics
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/237579c7-29ff-46b7-9f1e-0b4864830be4" width="600"></p>

### Bounding Box Count
<p align="center"><img src ="https://github.com/hyeseon-cpu/first/assets/128684012/90793b0e-ff38-481b-aa57-a082d731fe20" width="600"></p>
