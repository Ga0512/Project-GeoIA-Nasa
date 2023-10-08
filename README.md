# FindFire

## Overview
FindFire is an AI model solution that uses real-time satellite images to identify fires and notify government agencies

## Aplication
This AI (Artificial Intelligence) model captures multiple satellite images, identifying potential fires and notifying government agencies about their intensity, location, and time of occurrence. Based on the information received, government officials can take quick and effective actions to ensure public safety and environmental preservation.

## Automation
An example of usage would be automating a server that periodically fetches an image from NASA's Sentinel API (https://www.sentinel-hub.com/develop/api/) and passes it through our pre-trained model. If it detects a fire, it sends a notification.

## Notification (Example)
After identifying a fire, an email is sent to government agencies as shown in the image below:
![Image Email](https://github.com/Ga0512/Project-GeoIA-Nasa/assets/114010208/43f409cc-4f60-4d52-af2d-a38a1795f589)

In this format: [TIME] - Detected fire at [CITY], [STATE], [COUNTRY]. Click here for more detailed information: [LINK]

Being redirected to the link the content is at follows:

![Image Capture](https://github.com/Ga0512/Project-GeoIA-Nasa/assets/114010208/6af2b472-7935-4c44-856b-37b4eaec06e4)
![Image Result](https://github.com/Ga0512/Project-GeoIA-Nasa/assets/114010208/5043c644-ee87-4bd8-bdb0-f25ea68dd764)

Source: https://images.app.goo.gl/PrKkXcRhtpQCMuuq8 
## Resources
Trained model: https://drive.google.com/file/d/1meTbF6AZQOrT8CaN_s6pEGBX7vzsdT89/view

Dataset: https://universe.roboflow.com/fire-qgqmo/smoke-wildfire-dataset
