# 🚀 MediaPipe Computer Vision Showcase

Welcome to the `MediaPipe-Computer-Vision-Showcase` repository! This collection features various real-time computer vision projects built using Google's MediaPipe framework, integrated with OpenCV for robust image and video processing.

---

## ✨ Features

This repository demonstrates a wide array of MediaPipe capabilities, including:

-   ✋ **Hand Tracking:** Real-time detection and visualization of 21 3D hand landmarks.
    -   `Hand landmarks detection using MediaPipe.py`
    -   `Instant Motion Tracking with MediaPipe.py`
-   🧑‍💻 **Face Detection & Mesh:** Comprehensive face detection with bounding boxes, intricate 3D face mesh (468 landmarks), contours, and iris connections.
    -   `Object Detection with Web Cam using MediaPipe.py`
    -   `MediaPipe 3D Face Transform Code 1.py`
    -   `MediaPipe 3D Face Transform Code 2.py`
    -   `MediaPipe 3D Face Transform Code 3.py` (Includes face replacement/transformation)
-   🧍 **Pose Estimation:** Robust real-time human body pose tracking from webcam or video files, and static image analysis.
    -   `Pose Landmark Mediapipe.py`
    -   `Real-Time Body Pose Tracking.py`
    -   `Real Pose Tracking with Input Vedio.py`
    -   `MediaPipe 3D Face Transform Code 4.py` (Includes a basic clothing color change demo using pose)
-   👟 **3D Object Detection:** Detects and visualizes 3D bounding boxes and axes for specific objects (e.g., shoes, cameras) from images or video.
    -   `3D Object Detection.py`
    -   `3D Object Detection From Video.py`
-   🔗 **Holistic Tracking:** Combines face, hand, and pose landmark detection simultaneously in real-time, along with FPS display.
    -   `Face and Hand Landmarks Detection using Python – Mediapipe, OpenCV.py`

---

## 🛠️ Requirements

To run these projects, you'll need Python and the following libraries:

-   `opencv-python`
-   `mediapipe`
-   `numpy`
-   `matplotlib` (for `3D Object Detection.py` and `Pose Landmark Mediapipe.py`)
-   `Pillow` (for `3D Object Detection.py` - often installed with `opencv-python` but good to check)

You can install them using pip:

```bash
pip install opencv-python mediapipe numpy matplotlib Pillow
```

---

## 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [YOUR_REPO_URL]
    cd MediaPipe-Computer-Vision-Showcase
    ```
2.  **Navigate to the desired project:**
    ```bash
    cd [folder_name_if_any] # (e.g., if you organize them into subfolders)
    ```
3.  **Run the Python script:**
    ```bash
    python your_script_name.py
    ```

    * **Note:**
        * Some scripts use `cv2.VideoCapture(0)` for webcam input. Ensure your webcam is available and not in use by other applications.
        * Scripts like `3D Object Detection From Video.py` and `Real Pose Tracking with Input Vedio.py` require specific video file paths. Update these paths in the code to your local files.
        * `3D Object Detection.py` downloads an image from a URL, so an internet connection is required.
        * `Pose Landmark Mediapipe.py` loads an image from a local path, please update the path.

---

## 🤝 Contributing

Feel free to explore, fork, and contribute to this repository! If you have any suggestions or improvements, please open an issue or submit a pull request.

---

Enjoy exploring the power of MediaPipe and computer vision! 🌟
