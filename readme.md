# Lascade Task

## Description
You can view this app at [Task](https://lascade-task.vercel.app/).

## Specifications 
- **App**: This app is a web application built using HTML and JavaScript.

## Device Camera
- The back camera is used for the application.
- The following code is utilized for checking camera access and permissions:

    ```javascript
    navigator.mediaDevices.getUserMedia({
        video: {
            facingMode: 'environment'
        }
    });
    ```
- This will prompt the user for access to the back camera, and if it is not available, it will fall back to the front camera.

## Identification of Dominant Shapes
- Dominant shapes are identified based on their area.

## AR Framework Used
- A 3D environment has been developed using AR.js.
