# CV_CCP-Laiba-Wazir-
Assigment (23-AI-60)

# Complex Computing Problem

This project performs Human Activity Detection using **Python**, **OpenCV**, and **MediaPipe Pose Estimation**.  
The system analyzes a video, detects body landmarks, calculates knee joint angles, and identifies human activities such as:

- Walking
- Descending Movement
- Transition State

The project also generates a knee angle graph for motion analysis.

---

## Features
- Real-time pose detection
- Knee angle computation
- Activity classification using rule-based logic
- Video processing and output generation
- Angle variation graph visualization
- Works in Google Colab

---

## Technologies Used
- Python
- OpenCV
- MediaPipe
- NumPy


---

## Project Workflow
1. Load input video
2. Detect body landmarks using MediaPipe Pose
3. Extract hip, knee, and ankle coordinates
4. Compute knee joint angles
5. Apply rule-based activity detection
6. Display detected activity on video
7. Save processed output video
8. Download Video

---

## Knee Angle Calculation
The knee angle is calculated using:
- Hip coordinates
- Knee coordinates
- Ankle coordinates

The angle is computed using trigonometric calculations with NumPy.

## Activity Detection Logic

| Condition | Detected Activity |
|---|---|
| Downward body movement | Descending |
| Large knee angle | Walking |
| Intermediate movement | Transition |

---

## Output
The system produces:
- Processed video with pose landmarks
- Activity labels on frames
- Knee angle graph over time

---

## Sample Activities Detected
- Walking
- Descending Stairs
- Transition Movement

---

## How to Run

### Install Dependencies
```bash
pip install mediapipe opencv-python matplotlib numpy
```

### Run the Notebook
Open the Google Colab notebook and execute all cells sequentially.

---

## Repository Structure

```bash
├── notebook.ipynb
├── output.mp4
├── README.md
├── Input.mp4
└── CCP Report.pdf

```

---

## Applications
- Human motion analysis
- Fitness monitoring
- Activity recognition systems
- Surveillance systems
- Healthcare monitoring

---

## Future Improvements
- Deep learning-based activity recognition
- Multi-person tracking
- Real-time webcam support
- Higher activity classification accuracy

---

## Author
**Laiba Wazir**  
Roll No: 23-AI-60  
Section: B
