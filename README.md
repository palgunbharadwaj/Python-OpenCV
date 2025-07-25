# 🔫 Weapon Detection using Python-OpenCV

This project uses OpenCV and a Haar Cascade classifier to detect guns in real-time from a webcam feed.

## 📁 Files

- `gundetection.py`: Main Python script for gun detection.
- `cascade.xml`: Haar Cascade XML file for gun detection.

## 🛠️ Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- imutils

Install dependencies with:

```sh
pip install opencv-python numpy imutils
```

## 🚀 Usage

1. Ensure your webcam is connected.
2. Place `cascade.xml` and `gundetection.py` in the same directory.
3. Run the script:

```sh
python gundetection.py
```

4. A window will open showing the webcam feed. Detected guns will be highlighted with a rectangle.
5. Press **q** to quit.

## 🖨️ Output

- If a gun is detected during the session, the script prints **guns detected**.
- If no gun is detected, it prints **guns didn;t detected**.

## 📝 Notes

- The accuracy depends on the quality of the cascade file and the webcam.
- You can adjust detection parameters in the script for better results.
