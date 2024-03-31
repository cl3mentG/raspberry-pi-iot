
# Raspberry Pi-powered IoT Device

Below is the code for the IoT device I developed using a Raspberry Pi, a power bank, and various peripherals for the startup I co-founded from 2021 to 2024. As the Chief Technology Officer (CTO), I oversaw the development and implementation of this project.

The goal was to detect birds that landed in the field to deter them and avoid damages to crops and freshly sown seeds.

## Features

-   Image capture with a camera.
-   The camera can rotate a full 360 degrees.
-   Images can be processed locally with OpenCV.
-   Alerts can be sent using HTTP requests to a server.
-   Sound can be emitted if there are enough detections.
-   Snooze mode in between detection batches: The Raspberry Pi can be shut down to save power and then woken up using the watchdog hat.

## Folder Structure

-   `hardware`: Contains a description of the Raspberry Pi box. Pieces used are listed, and there are 3D models of the camera mount as well as a few pictures of the component layout in the waterproof box.
-   `code`: Contains the code that was used to run on the Raspberry Pi for detecting birds.
