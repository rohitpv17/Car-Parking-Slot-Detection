# 🚘 Car Parking Slot Detection

## Table of Contents
- Project Overview
- Key Functionalities
- Technologies Used
- Screenshots
- Deployment
- Usage

## Project Overview
Efficient parking management is a crucial component of urban infrastructure, and technology can play a vital role in optimizing parking slot usage. This Car Parking Slot Detection system is designed to provide a computer vision based solution for detecting available and occupied parking slot in real time. The system utilizes OpenCV to process video, identify parking slot, and determine their status. It is an ideal solution for smart parking applications.

## Key Functionalities
- **Manual Parking Slot Selection:** Users can mark parking slot manually on an image.
- **Automated Detection:** Using OpenCV, the system continuously analyzes frames to detect whether the marked parking slot is occupied or empty.
- **Real Time Processing:** The system is capable of working on live video feeds or pre recorded footage to provide instant feedback.
- **Web Based Interface:** A user friendly interface built with Flask allows users to monitor parking space availability through a browser.

## Technologies Used
- OpenCV
- Flask
- HTML
- CSS
- JavaScript
- Render

## Screenshots

![](https://github.com/rohitpv17/Car-Parking-Slot-Detection/blob/main/screenshots/screenshot%201.jpg)

![](https://github.com/rohitpv17/Car-Parking-Slot-Detection/blob/main/screenshots/screenshot%202.jpg)

![](https://github.com/rohitpv17/Car-Parking-Slot-Detection/blob/main/screenshots/screenshot%203.jpg)

![](https://github.com/rohitpv17/Car-Parking-Slot-Detection/blob/main/screenshots/screenshot%204.jpg)

## Deployment
The project is deployed on Render, enabling remote access and real time parking slot detection via a web interface.
<br>[Deployment](https://carparkingslot.onrender.com/)

## Usage
- Clone the Repository
```Bash
    https://github.com/rohitpv17/Car-Parking-Slot-Detection.git
```
- Change the Directory
```Bash
    cd Car-Parking-Slot-Detection
```
- Install the Dependencies
```Bash
    pip install -r requirements.txt
```
- Run the Flask Application
```Bash
    python app.py
```
