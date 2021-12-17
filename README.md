# Speeding Monitor System

Driving around Ithaca is challenging due to the narrow streets with steep slopes and sharp turns. Speed limitation is a good way to ensure safe driving under such road conditions. This Speeding Monitor project intends to implement a device that can be placed at the roadside measuring the speed of passing vehicles. The project used Raspberry Pi 4 to be the microcontroller; two ultrasonic sensors to measure and calculate the speed of cars, and a Raspberry Pi Camera to capture an image of the license plate. The OpenCV library was used to process the captured image to crop the area of the license plate. Finally, optical character recognition (OCR) was used to transform the image into text information. A local server on Raspberry Pi was also set up so that the detected history over a speeding car with its license plate can be displayed on a website.
