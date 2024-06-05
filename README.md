# MUNQIDH

**MUNQIDH** is an advanced drone-based system aimed at enhancing search and rescue operations in aquatic emergencies such as floods. The project incorporates live video streaming, real-time object detection, and geographic information systems to locate and assist distressed individuals.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Collection](#data-collection)
- [Contributing](#contributing)
- [Conclusion](#Conclusion)
- [Future Work](#Future-Work)

## Introduction
MUNQIDH leverages drone technology to perform real-time surveillance and detection in flood-affected areas. Using a DJI Mini 2 drone, the system streams live video feeds, detects people and vehicles stranded in floods, and marks their locations on a map. This information is then relayed to the relevant authorities to facilitate prompt rescue operations.

## Features
- **Real-Time Video Streaming:** The drone streams live video feeds which are displayed on a website using Streamlit.
- **Object Detection:** Utilizes YOLO algorithm for real-time detection of people and vehicles.
- **Geographic Information System (GIS):** Marks the location of detected individuals on a map.
- **Automated Reporting:** Sends reports to relevant authorities once individuals are detected.

## Installation
### Prerequisites
- Python 3.7 or later
- DJI SDK
- Streamlit
- OpenCV
- YOLOv8

### Steps
1. Clone the repository:
    ```sh
    git clone https://github.com/661abdullah/MUNQIDH.git
    ```
2. Navigate to the project directory:
    ```sh
    cd MUNQIDH
    ```
3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. **Start the Streamlit application:**
    ```sh
    streamlit run app.py
    ```
2. **Connect the DJI Mini 2 drone:**
   Follow the DJI SDK instructions to connect and control the drone.

3. **Begin the surveillance operation:**
   Use the provided interface to start the drone's live video feed and detection system.

4. **Monitoring and Reporting:**
   The application will display the video feed and mark detected individuals' locations on the map. Reports are generated automatically and sent to the authorities.

## Data Collection
All data for the project was collected manually, then we label the data using roboflow. This data was then used to train and fine-tune the YOLO model for accurate object detection.
Dataset link - > https://app.roboflow.com/t5-rkshu/final-muucf/1

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Conclusion
The MUNQIDH project has demonstrated the potential of using drone technology to significantly improve search and rescue operations during aquatic emergencies. The integration of real-time video streaming, object detection, and GIS mapping has provided a robust solution for locating and assisting individuals in distress. The success of the MUNQIDH system highlights the importance of innovative approaches in enhancing emergency response capabilities.

## Future Work
While MUNQIDH has achieved its primary objectives, there are several areas for future improvement and expansion:
- **Enhanced Object Detection:** Further training the YOLO model with a larger and more diverse dataset to improve accuracy in different environmental conditions.
- **Integration with Emergency Services:** Developing more sophisticated communication protocols to integrate seamlessly with emergency service dispatch systems.
- **Battery Life and Range:** Exploring advancements in drone technology to extend battery life and operational range, allowing for more extensive search and rescue operations.
- **Machine Learning Improvements:** Implementing advanced machine learning techniques to better predict and identify potential areas of distress during floods.
- **User Interface Enhancements:** Improving the user interface for easier operation and more intuitive interaction with the system.

By focusing on these areas, the MUNQIDH project can continue to evolve and provide even greater support in emergency situations, ultimately saving more lives and reducing the impact of natural disasters.


