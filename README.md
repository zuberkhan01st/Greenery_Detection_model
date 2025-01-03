# Greenery Detection Model

The **Greenery Detection Model** is a machine learning project designed to detect greenery in images, helping promote sustainability and green initiatives. This application leverages computer vision techniques to analyze images and identify areas of greenery.

## Project Overview

The Greenery Detection Model:
- Processes uploaded images to identify and highlight greenery.
- Provides visual outputs to show detected green areas.
- Supports environmental monitoring and sustainability efforts.

This project is ideal for:
- Environmental studies.
- Urban planning to monitor greenery coverage.
- Promoting awareness of green spaces.

## Features

- **Image Upload**: Easily upload images for analysis.
- **Greenery Detection**: Utilizes machine learning techniques to identify greenery in the uploaded images.
- **Interactive Results**: Displays processed images with highlighted greenery areas.
- **User-Friendly Interface**: Simple and intuitive web interface for users.

## Technologies Used

- **Backend**: Python (Flask)
- **Frontend**: HTML, CSS
- **Machine Learning**: OpenCV, NumPy
- **Deployment**: Procfile for Heroku or other cloud platforms

## Repository Structure
Greenery_Detection_model/
│
├── processed/                  # Folder containing processed image files
├── templates/                  # HTML templates for the web application
│   ├── index.html              # Main page for uploading images
│   ├── results.html            # Results page displaying detected greenery
│
├── uploads/                    # Directory for storing uploaded images
│
├── .gitignore                  # Specifies files to ignore in the repository
├── Procfile                    # Configuration file for deployment
├── requirements.txt            # List of Python dependencies
├── tree_pip.py                 # Main Python script for running the application
└── README.md                   # Documentation for the project
