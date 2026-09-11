<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# Aana Vaayil Ambazhanga 🎯


## Basic Details
### Team Name: Jwala


### Team Members
- Team Lead: Elena Elizhiba Sony - Mar Baselios Christian College Of Engineering And Technology Peermade Kuttikkanam
- Member 2: Sivani S - Mar Baselios Christian College Of Engineering And Technology Peermade Kuttikkanam
- Member 3: [Name] - [College]

### Project Description
A fun computer vision application that checks how close a small yellow/orange fruit is to an elephant’s mouth. It uses AI and image processing to turn the Malayalam proverb “Aana Vaayil Ambazhanga” into a humorous technical project.
The Problem (that doesn't exist)

### The Problem (that doesn't exist)
How can we determine whether a tiny fruit is close enough to an elephant’s mouth? This completely unnecessary system attempts to solve this extremely important problem.


### The Solution (that nobody asked for)
The application detects an elephant using YOLOv8 and identifies a possible yellow/orange fruit using OpenCV color segmentation. It estimates the elephant’s mouth region, calculates the distance to the fruit, and produces a funny compatibility score.
## Technical Details
### Technologies/Components Used
For Software:
Language: Python
Framework/GUI: Tkinter
Libraries: OpenCV, NumPy, Ultralytics YOLOv8, Pillow
AI Model: YOLOv8n
Tools: VS Code/Antigravity, Python, GitHub


For Hardware:
Main components: Laptop/PC, Webcam (optional)
Specifications: Minimum 4 GB RAM, Python-supported processor, sufficient storage
Tools required: Camera/Webcam for live detection 
### Implementation
For Software:
# Installation
git clone <your-github-repository-url>
cd elephantfruit
pip install -r requirements.txt

# Run
python main.py

### Project Documentation
For Software:

# Screenshots (Add at least 3)
<img width="1915" height="986" alt="Main application interface" src="https://github.com/user-attachments/assets/0c1a0542-e699-43a4-b0ea-d398219bd202" />

 Main Application Interface
Shows the main Tkinter interface with options to start/stop the camera, upload an image, reset the analysis, and generate the final report.

<img width="1917" height="978" alt="elephant and fruit detection" src="https://github.com/user-attachments/assets/2be3c684-e781-4b63-85df-c0477dffb928" />

Elephant and Fruit Detection
Shows the detected elephant with its bounding box and the identified yellow/orange fruit using OpenCV color segmentation.

<img width="1902" height="965" alt="compatibility analysis" src="https://github.com/user-attachments/assets/172e163c-4a4b-4368-a968-4faf1b34a658" />

 Compatibility Analysis
Shows the estimated elephant mouth region, distance between the fruit and mouth, and the generated compatibility score.
# Diagrams
Workflow:
Input Image / Webcam
        ↓
Elephant Detection
      (YOLOv8)
        ↓
Fruit Detection
(OpenCV HSV + Contours)
        ↓
Estimate Elephant Mouth
        ↓
Calculate Distance
        ↓
Calculate Compatibility Score
        ↓
Display Result in GUI
Caption:
The workflow shows how the application processes an image or webcam frame, detects the elephant and possible fruit, estimates the mouth position, calculates their distance, and generates the final compatibility score.

For Hardware:

# Schematic & Circuit
![Circuit]Not applicable. This project is a software-based computer vision application and does not require electronic circuits or physical components.

![Schematic]The system architecture consists of an input image/webcam feed, YOLOv8 elephant detection, OpenCV fruit detection, mouth-region estimation, distance calculation, and compatibility-score generation.

# Build Photos
![Components]Not applicable. The project is implemented entirely in software using Python, OpenCV, YOLOv8, NumPy, and Tkinter.

![Build]The application was developed by integrating YOLOv8 for elephant detection, HSV-based color segmentation for identifying the possible fruit, geometric calculations for measuring the distance, and a Tkinter interface for displaying the results.

![Final]The final application provides image upload and webcam-based analysis and displays the detected elephant, possible fruit, estimated mouth position, distance, and compatibility score.
### Project Demo
# Video

*Explain what the video demonstrates*

# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- [Name 1]: [Specific contributions]
- [Name 2]: [Specific contributions]
- [Name 3]: [Specific contributions]

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



