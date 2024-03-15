# PCSE24-18
# Self-Driving Car with Deep Learning and IoT

This repository contains a C++ implementation of a self-driving car system utilizing deep learning and IoT technologies. The system is designed to capture real-time images from a camera module, process them using computer vision algorithms, detect lane markings, objects, traffic signs, and make driving decisions accordingly.

## Features

- Real-time image processing
- Lane detection and tracking
- Object detection
- Traffic sign detection
- Automatic driving decisions based on detected objects and lane markings
- IoT integration for controlling external devices (e.g., motors, lights)

## Requirements

- OpenCV 2.4.13 or later
- Raspicam library
- WiringPi library

## Installation

1. Clone this repository:

```bash
git clone https://github.com/username/repo.git
```

2. Install OpenCV, Raspicam, and WiringPi libraries according to their respective documentation.

3. Compile the code using a C++ compiler.

## Usage

1. Connect the camera module to your Raspberry Pi.
2. Run the compiled executable with appropriate arguments to set camera parameters.
3. The system will start capturing and processing images in real-time.
4. Detected objects, lane markings, and driving decisions will be displayed on the screen.
5. IoT integration allows for controlling external devices based on detected conditions.

## Code Structure

- `main.cpp`: Main entry point of the program, contains the main logic for image processing, object detection, and driving decisions.
- `utils.cpp`: Utility functions for camera setup, image processing, and object detection.
- `cascade_files/`: Contains XML files for object detection using Haar cascades.
- `images/`: Placeholder directory for sample images.

## Contributors

- Harshit Sharma (@harshit6981)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to [OpenCV](https://opencv.org/) and [Raspicam](https://www.uco.es/investiga/grupos/ava/node/40) for their excellent libraries and documentation.
- Inspired by advancements in autonomous driving technology.
