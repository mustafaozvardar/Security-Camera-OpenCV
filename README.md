# 🎥 Motion Detection Security Camera

This is a simple Python-based security camera application that uses motion detection. It captures video from your webcam, detects any movement, and triggers a beep sound when significant motion is detected.

## Features ✨

- 📷 Captures video from your webcam in real-time.
- 🎯 Detects motion by comparing consecutive video frames.
- 🔊 Triggers a beep sound when significant motion is detected.
- 🛑 Easy to stop by pressing the `Esc` key.

## Requirements 📦

- Python 3.x
- `opencv-python` library
- `winsound` module (built-in with Python on Windows)
- A working webcam

## Installation 🚀

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/motion-detection-camera.git
    cd motion-detection-camera
    ```

2. Install the required library:

    ```bash
    pip install opencv-python
    ```

## Usage 🎤

1. Run the script:

    ```bash
    python security_camera.py
    ```

2. The application will start capturing video from your webcam. When it detects significant motion, it will trigger a beep sound to alert you.

3. To stop the application, press the `Esc` key.

## Troubleshooting 🛠️

- Ensure your webcam is properly connected and recognized by your computer.
- The script may require adjustments based on lighting conditions and sensitivity.

## License 📜
This project is licensed under the MIT License - see the LICENSE file for details.
