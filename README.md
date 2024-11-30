# IntelligentViolenceDetection
This project aims to detect humans and violent actions in videos, extract frames of interest, and generate alerts. The identified frames are stored in a cloud database for further analysis, designed for public safety and security monitoring.

## Features

1. **Human Detection**:
   - Identifies individuals in video frames using advanced computer vision techniques.
   - Utilizes pre-trained models for accuracy.

2. **Violence Detection**:
   - Analyzes video frames to detect violent actions.
   - Extracts specific frames involving violence for storage and review.

3. **Alert System**:
   - Triggers alerts when violent activity is detected.
   - Provides real-time feedback for security personnel.

4. **Cloud Integration**:
   - Stores violent frames in a Firebase database for centralized access.

5. **Demo Video**:
   - Demonstrates the system's capabilities and features.

## Folder Structure

- **Alert System**: Code and configurations for the alerting mechanism.
- **Completed Project**: Consolidated implementation of all features.
- **demo video**: A sample video showcasing the project's functionality.
- **Human Detection**: Modules and code for detecting humans in videos.
- **model.json**: Contains the model architecture or parameters used in the project.
- **Violence Detection**: Logic and implementations for identifying violent actions.

## Getting Started

### Prerequisites

- Python 3.x
- Install required libraries
- Firebase account for cloud integration.

## Installation
Clone the repository:
git clone https://github.com/Rohansardesai23/IntelligentViolenceDetection.git
cd IntelligentViolenceDetection
Set up Firebase credentials in the project.

## Usage
Upload a video file for analysis.
The system will:
Detect humans.
Analyze actions for violent behavior.
Extract and store violent frames in Firebase.
Trigger an alert if necessary.
Review results via the cloud database or local storage.
