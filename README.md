# AzureFaceRecognition

A simple android prototype app that uses Microsoft Azure's Face SDK to detect faces on 2 pictures, and then verify the first face found in one picture with the first in the other picture.

The application asks for internet permission to connect to the Azure cloud and do the detection and verification. 

The application also gets the pictures from the device storage and asks access to it.

## Getting Started 

Microsoft Face API:

https://azure.microsoft.com/en-us/services/cognitive-services/face/

To get started, you need the `apiEndpoint` and the `subscriptionKey` that you get after signing up to use the API. 

Import the project in your Android Studio, then add the `apiEndpoint` and the `subscriptionKey` to the `MainActivity.java` class, and then start the application (on the virtual machine or an android device).
