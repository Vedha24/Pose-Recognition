# Pose Recognition 

## Overview
This project implements a pose recognition system using computer vision techniques. It leverages OpenCV and MediaPipe to detect and annotate human poses in images, videos, and live webcam feeds. The project is designed for educational and demonstration purposes, as part of a Computer Science curriculum.

## Features
- Detects human poses in images, video files, and live webcam streams
- Annotates detected poses with landmarks and connections
- Saves annotated outputs for both images and videos
- User-friendly command-line interface

## Requirements
- Python 3.7+
- OpenCV (`cv2`)
- MediaPipe (`mediapipe`)
- (Optional) A webcam for live pose detection

## Installation
1. Clone or download this repository.
2. Install the required packages:
   ```bash
   pip install opencv-python mediapipe
   ```

## Usage
Run the main script:
```bash
python pose_recognition.py
```

You will be prompted to choose a mode:
1. **Photo**: Enter comma-separated image file paths to annotate.
2. **Video**: Enter comma-separated video file paths to annotate.
3. **Webcam**: Start live pose detection using your webcam.

### Inputs & Outputs
- Place your input files in the `INPUTS` folder for convenience (optional).
- Annotated images and videos will be saved in the `OUTPUTS` folder or as specified in the script.
- Annotated webcam output is saved as `annotated_webcam_output.avi`.

## File Structure
- `pose_recognition.py`: Main script for pose detection

## Notes
- Press `q` during video or webcam display to exit.
- Ensure your input file paths are correct.
- For best results, use clear images/videos with visible human figures.


