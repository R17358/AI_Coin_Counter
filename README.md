# AI-Coin-Counter

## Overview
**AI-Coin-Counter** is a Python-based web application that automatically detects and counts Indian coins from an image and calculates the total accumulated amount. It utilizes **OpenCV** for image processing and coin detection, providing an efficient and user-friendly interface.

## Features
- ✅ **Automatic Coin Detection** – Identifies and counts coins from an uploaded image.
- ✅ **Indian Currency Support** – Recognizes various Indian coin denominations.
- ✅ **Amount Calculation** – Computes the total value of detected coins.
- ✅ **Web-Based Interface** – Uses Flask/Streamlit for user interaction.
- ✅ **OpenCV-Powered Processing** – Implements image processing techniques for accurate detection.

## Tech Stack
- **Python** – Core programming language
- **OpenCV** – For image processing and coin detection
- **Flask/Streamlit** – For web-based interface
- **NumPy** – For mathematical operations
- **Matplotlib** – For visualization (if needed)

## How It Works
1. **Upload an Image** – Users provide an image of coins.
2. **Preprocessing** – Converts image to grayscale and applies noise reduction.
3. **Edge Detection** – Uses Canny Edge Detection and contour detection to identify coins.
4. **Coin Identification** – Detects different coins based on size and shape.
5. **Amount Calculation** – Computes the total value of all detected coins.
6. **Result Display** – Displays the counted coins and the accumulated amount.

## Installation
### Prerequisites
Make sure you have Python installed (>= 3.7) and install the required dependencies:
```bash
pip install opencv-python numpy matplotlib flask streamlit
```

### Running the Application
```bash
python app.py
```
For Streamlit-based UI, run:
```bash
streamlit run app.py
```

## Usage
1. Open the web application.
2. Upload an image of coins.
3. Click "Detect Coins" to process the image.
4. View the detected coins and the total amount.

## Future Enhancements
- 🔥 **Deep Learning Integration** – Enhance accuracy using TensorFlow/Keras.
- 📱 **Mobile Support** – Convert into a mobile-friendly application.
- 🎥 **Real-Time Detection** – Enable live video coin detection.
- 🌍 **Multi-Currency Support** – Extend detection for other currencies.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the **MIT License**.

---
🚀 **AI-Coin-Counter – Automate Coin Counting with AI!**

