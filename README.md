# Brightness Control Using Hand Gestures

This is a simple Python project that allows you to control your screen brightness using hand gestures via a webcam.

## Features
- Uses **OpenCV** and **MediaPipe** for real-time hand tracking
- Adjusts brightness based on the distance between thumb and index finger
- Works with multiple screens
- Runs efficiently on most Windows devices

## Requirements
Ensure you have the following installed:

```sh
pip install opencv-python mediapipe screen-brightness-control numpy
```

## How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/ThakurAmanKumar/BrightnessControl.git
   ```
2. Navigate to the project directory:
   ```sh
   cd BrightnessControl
   ```
3. Run the script:
   ```sh
   python brightness_control.py
   ```
4. If administrator permission is required, run:
   ```sh
   powershell Start-Process -Verb RunAs python.exe brightness_control.py
   ```

## How It Works
- The webcam detects your hand.
- When you bring your thumb and index finger close, the brightness decreases.
- When you move them apart, the brightness increases.
- Press **'q'** to exit the application.

## Stop the Script
To stop the script, go to the terminal and press:
```sh
CTRL + C
```

## Demo Video
[![Watch the video](https://img.youtube.com/vi/VIDEO_ID_HERE/maxresdefault.jpg)](https://www.linkedin.com/feed/update/urn:li:activity:7301916149514977280)

## 📜 License
This project is licensed under the **MIT License**.  
See the full license [here](https://github.com/ThakurAmanKumar/License/blob/main/LICENSE).


---

Made with ❤️ by [Thakur Aman Kumar](https://github.com/ThakurAmanKumar)
