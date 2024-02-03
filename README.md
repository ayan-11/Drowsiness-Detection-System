# Drowsiness Detection System

## Overview

The Drowsiness Detection System is an end-to-end deployed project designed to prevent accidents caused by drowsy driving. Using computer vision techniques, specifically HAAR cascades and OpenCV, the system monitors the driver's eyes and alerts them if signs of drowsiness are detected.

## Features

- **Real-time Monitoring:** Continuously monitors the driver's eyes in real-time to detect signs of drowsiness.
- **HAAR Cascade Classifier:** Utilizes a pre-trained HAAR cascade classifier for eye detection.
- **Alert Mechanism:** Issues an alert, such as an alarm or notification, when drowsiness is detected.
- **User-Friendly Interface:** Provides a simple and intuitive interface for both monitoring and configuration.

## Getting Started

To get started with the Drowsiness Detection System, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ayan-11/Drowsiness-Detection-System.git
   ```

2. **Install Dependencies:**
   ```bash
   cd Drowsiness-Detection-System
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```bash
   python main.py
   ```

4. **Configure Settings:**
   Adjust settings, such as alert type and detection sensitivity, in the configuration file (`config.json`).

5. **Deploy the System:**
   Deploy the system in your vehicle or testing environment, ensuring the camera has a clear view of the driver's face.

## Technologies Used

- Python
- OpenCV
- HAAR Cascade Classifier
- Alert System (e.g., sound alarm, notifications)
- Tkinter (for the GUI)

## Deployment

The Drowsiness Detection System can be easily deployed in vehicles or testing environments. Ensure proper camera placement and lighting for optimal performance.

## Contributing

We welcome contributions from the community. If you'd like to contribute, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the OpenCV community for their valuable contributions to computer vision.

Feel free to reach out with any questions or feedback. Drive safely! 🚗😴
