# traffic_py
# Smart Traffic Management System

## Overview
This project utilizes AI-powered car detection and dynamic traffic signal control to optimize traffic flow. The system detects vehicles in real-time using OpenCV and controls signals based on car density.

## Features
- **Car Detection**: Uses OpenCV's Haar cascades to detect vehicles in images.
- **Traffic Signal Control**: Adjusts signals dynamically based on detected car counts.
- **Real-Time Image Processing**: Supports live video processing.
- **Web Dashboard (Upcoming)**: A Flask-based interface to visualize traffic data.

## Installation
### Prerequisites
Ensure you have Python 3 installed. Install dependencies using:
```sh
pip install opencv-python numpy flask
```

### Clone the Repository
```sh
git clone https://github.com/yourusername/smart-traffic-management.git
cd smart-traffic-management
```

## Usage
### Run Car Detection
1. Place a traffic image (`traffic.jpg`) in the project directory.
2. Run the detection script:
```sh
python smart_traffic_ai.py
```

### Expected Output
- The number of detected cars is printed.
- The traffic signal logic is displayed.
- A window shows the detected cars in the image.

## Upcoming Features
- **Flask Web App** for real-time visualization.
- **Live Video Processing** using traffic cameras.

## Contributing
Pull requests are welcome. Please ensure your code is well-documented.

## License
MIT License.
