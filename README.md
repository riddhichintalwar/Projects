# Color Detection Tool

A Python application that detects colors in an image interactively. It identifies the color name along with its RGB values based on user input. Built using OpenCV and Pandas, this tool is ideal for exploring color detection concepts.

## Features
- Detect colors by double-clicking on an image.
- Display the color name along with RGB values.
- Dynamically adjusts text color for better visibility against different backgrounds.

## Installation

### Prerequisites
- Python 3.7 or above
- Libraries: `opencv-python`, `pandas`

### Install the required dependencies:
pip install -r requirements.txt

###Project Workflow
1.Image Processing:Load and resize the input image using OpenCV.
Color Dataset:
2.Reads a CSV file (colors.csv) containing predefined color names and RGB values.
3.Color Matching:
Uses a distance-based algorithm to find the closest color name from the dataset.
4.Interactive Detection:
Tracks mouse clicks to identify and display the color dynamically.

###Technologies Used
1.Python
2.OpenCV: For image processing and GUI interaction.
3.Pandas: For managing and querying the color dataset.

###Contributing
 Contributions are welcome! To contribute:

1.Fork this repository.
2.Create a new branch:
  git checkout -b feature-name
3.Make your changes and commit them.
4.Push to the branch:
  git push origin feature-name
5.Open a pull request.



