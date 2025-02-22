**Image Steganography Encoder-Decoder**


Overview

This project implements image steganography using OpenCV, allowing users to hide and retrieve secret messages within an image’s pixel data. It ensures covert communication by modifying pixel values without noticeable changes.


Features

Hide secret messages inside an image
Retrieve the hidden message using a passcode
Simple and lightweight implementation
Uses pixel-level encoding for secure message concealment
Works on Windows (can be adapted for Linux/MacOS)


Technologies Used

Python – Core programming language
OpenCV (cv2) – For image processing
OS module – For file handling
String manipulation – Encoding and decoding messages


How It Works

Encoding:
The user inputs a secret message and a passcode.
The message is embedded into the image’s pixel values.
The modified image is saved as encryptedImage.jpg.

Decoding:
The user provides the correct passcode.
The hidden message is extracted from the image.
If the passcode is incorrect, access is denied.


Setup & Usage

Prerequisites
Make sure you have Python installed and the required library:

`pip install opencv-python`

Running the Program
1. Clone the repository:
```
git clone https://github.com/prateek-d-y/steganography.git
cd steganography.git
```
2. Run the script:

`python steganography.py`

3. Enter your secret message and passcode when prompted.


Future Scope

Improve encryption for better security
Support for multiple image formats
Develop a GUI-based version for ease of use
Implement advanced steganography techniques


Contributors

Feel free to contribute by submitting pull requests or reporting issues!


License

This project is licensed under the MIT License.
