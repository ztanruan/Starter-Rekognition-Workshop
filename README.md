## Amazon Rekognition Celebrity and Label Detection iOS

## Acknoledgment 

Special thanks to Prashant Pawan (Principal PMT - AWS ML - SageMaker Notebooks), Henri Yandell, Dennis Hills, 
and Mobile Quickie for their contribution to iOS Amazon Rekognition starter source code

Starter iOS Swift project code for identifying celebrities and label detection using Amazon Rekognition

### Overview of the starter app

The starter app includes the basic plumbing for capturing a picture using
the device camera, or selecting a photo from the device photo library. It also
includes components that can load a webpage inside a Safari-based
webview.

Also, the starter app includes a Celebrity.swift and Object.swift class. 
Each class is use to create an object to identified the face or label in the provided image.
This object uses results from the Amazon Rekognition API to populate its
properties and identify the location of each identified 'face' or label in the image. In
particular, it uses the bounding box data for each face or label that’s identified in
the image, and draws a button at the position of the face or label.


## License Summary

This sample code is made available under a modified MIT license. See the LICENSE file.
