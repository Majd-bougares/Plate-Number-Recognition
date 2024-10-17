# Plate Number Recognition

This project implements a plate number recognition system capable of detecting and reading license plates from either video feeds of moving cars or static images. It leverages YOLOv8 for object detection and EasyOCR for text recognition. The goal is to extract and display the plate numbers detected in each frame.


## Features
- Detects license plates in both videos and images
- Supports real-time detection on video streams
- Reads and extracts text from detected plates
- Saves processed results for later analysis


## Installation
To get started, clone the repository and install the required packages.

### Prerequisites
- Python 3.8+
- pip (Python package installer)


### YOLOv8 Setup
You'll need to set up YOLOv8 for object detection. Install the ultralytics package:
```bash
pip install ultralytics
```

## Usage
The system can be used with both images and videos.

## Results
After processing, the system displays each frame or image with detected plates highlighted and the plate numbers extracted using OCR. Processed results can also be saved to a specified directory.

### Example Output
*Provide example images showing the system's detection and recognition output.*

## Technologies Used
- **Python** - Main programming language
- **YOLOv8** - Used for object detection
- **EasyOCR** - Used for text recognition on detected plates


## Acknowledgments
- YOLOv8 by Ultralytics for fast and accurate object detection.
- EasyOCR for reliable optical character recognition on license plates.
- Sort : A simple online and realtime tracking algorithm for 2D multiple object tracking in video sequences
@inproceedings{Bewley2016_sort,
  author={Bewley, Alex and Ge, Zongyuan and Ott, Lionel and Ramos, Fabio and Upcroft, Ben},
  booktitle={2016 IEEE International Conference on Image Processing (ICIP)},
  title={Simple online and realtime tracking},
  year={2016},
  pages={3464-3468},
  keywords={Benchmark testing;Complexity theory;Detectors;Kalman filters;Target tracking;Visualization;Computer Vision;Data Association;Detection;Multiple Object Tracking},
  doi={10.1109/ICIP.2016.7533003}
}
