# Vehicle Tracking Project

This repository contains code for a vehicle tracking model developed using OpenCV and YOLOv8 which supports a range of vision AI tasks, including detection, segmentation, tracking, and classification. This project aims to track various objects throughout a video and determine the number of vehicles leaving and entering the frame. This code serves as a preliminary implementation for detecting traffic congestion. It sets up the necessary parameters and initial configurations for analyzing traffic patterns.

## Run the Notebook on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayhixza/vehicle-tracking/blob/main/vehicle_tracking.ipynb)

### How to Use the Colab Notebook

To run this project in Google Colab, click the "Open in Colab" button above. Follow these simple steps to set it up:

1. **Click the "Open in Colab" button** above to open the notebook in Google Colab.
2. **Run the setup cell**: The first cell installs all necessary libraries and mounts Google Drive if needed. You only need to do this once.
3. **Follow the notebook instructions**: Run each cell in order to execute the code and see the results.

**Note**: You must have a Google account to use Google Colab.

### Requirements

- Google Account to access Google Colab.
- Python dependencies specified in the `requirements.txt` file (automatically installed in the setup cell).
  
Below is an example of a processed frame from the video. (Sample video source: https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/)

![sample-output](https://github.com/user-attachments/assets/ed428fcf-b5d7-4635-8efa-748ff4ec3f27)

You can change and experiment with other parameters supported by YOLOv8 to build upon this project using different datasets.
