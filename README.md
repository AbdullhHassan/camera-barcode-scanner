# camera-barcode-scanner
This is a Python application that allows you to scan QR codes using your camera and search for the scanned code in an Excel database.


# QR Code Scanner

This is a Python application that allows you to scan QR codes using your camera and search for the scanned code in an Excel database.

## Prerequisites

- Python 3.7 or above
- OpenCV (cv2) library
- pyzbar library
- openpyxl library

## Installation

1. Clone the repository:

```shell
git clone https://github.com/your-username/qr-code-scanner.git
Navigate to the project directory:
shell
Copy code
cd qr-code-scanner
Install the required libraries:
shell
Copy code
pip install opencv-python pyzbar openpyxl
Usage
Ensure that your camera is connected to your computer.

Run the script:

shell
Copy code
python main.py
The application will open a camera feed window. Hold a QR code in front of the camera to scan it.

The scanned QR code will be searched in the Excel database. If a match is found, the corresponding member code will be displayed. Otherwise, a "Member not found" message will be shown.

Press 'q' to exit the application.

Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
