# CODERECET

## Project Repository
*Commit and save your changes here*

### Team Name : Oreo Shake
### Team Members : Liya Mary Koshy, Gauri G Thampi, Devanandana P R

### Project Description
Communication barriers often limit the participation of the deaf and hard-of-hearing community in mainstream society. American Sign Language (ASL) is the primary mode of communication for many, but the lack of widespread interpreters and accessibility tools creates challenges in daily interactions. Our proposed solution, SignSpeak, is an AI-powered software that translates ASL gestures into real-time text and audio, facilitating seamless communication.

## Technical Details and Technologies/Components Used

## For Software:
Languages Used:
Python
JavaScript
HTML
CSS

Frameworks Used:
TensorFlow / Keras

Libraries Used:
OpenCV
MediaPipe
NumPy
scikit-learn
TensorFlow.js

Tools Used:
VS Code
GitHub

## Implementation

## For Software:

### Installation
# Clone repository
git clone https://github.com/oreoshake2025/SignSpeak.git
cd SignSpeak

# Set up virtual environment
python -m venv new
.\new\Scripts\activate

# Install dependencies
pip install -r requirements.txt


### Run
# Run the frontend (open index.html in browser)
# Run the backend (camera-based Python detection)
python camera.py

### Project Documentation
The model detects hand gestures using MediaPipe.
Landmark data is passed to a CNN model trained on ASL letter datasets.
Detected letters are displayed live in the frontend.
Optional: Converts letters to audio using text-to-speech.

### Screenshots (Add at least 3)
<img width="1895" height="860" alt="Screenshot 2025-07-26 153245" src="https://github.com/user-attachments/assets/f915f301-fda9-477f-a9d4-11529a947bb2" />

### Diagrams

![WhatsApp Image 2025-07-26 at 18 36 44_7dd32aee](https://github.com/user-attachments/assets/6e03bf26-1ad9-4e15-ab17-a37c402ff5cc)

## Team Contributions
Liya Mary Koshy:Frontend
Gauri G Thampi: Model Training
Devanandana P R:Backend
