# Face-Tracking Robot

This project demonstrates a simple face-tracking robot that uses a camera to detect and track human faces. The robot points a laser light at the detected faces. The implementation uses OpenCV for face detection, and an Arduino board to control the laser light and the wheels of the rover. The pyFirmata is a package that enables you to write the Arduino code in Python.

## Packages Required

1. **cvzone** (includes OpenCV and NumPy)
2. **pyfirmata**

## Installation

To get started, you'll need to install the required Python packages. You can do this using `pip`.

```bash
pip install cvzone pyfirmata
