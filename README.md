# QR-Code_Generator-Python
This repository contains a simple Python script that utilizes the qrcode library to generate a QR code image. The script encodes a specified URL and creates a QR code image that can be scanned by QR code readers.
# QR Code Generator

![Generated QR Code](GIT_CODE.png)

## Features

- Generates a QR code with customizable settings such as version, box size, and border.
- Encodes a URL, in this case, the GitHub profile URL `https://github.com/omoke664`.
- Creates a QR code image with a black foreground and white background.
- Saves the generated QR code image as "GIT_CODE.png" in the repository directory.

## Usage

1. Clone or download this repository to your local machine.
2. Install the required `qrcode` library (if not already installed) using `pip install qrcode[pil]`.
3. Open and run the `generate_qrcode.py` script using Python.
4. The script will generate a QR code image named "GIT_CODE.png" in the same directory.
5. The generated QR code can be scanned by any QR code reader app.

Feel free to modify the script to encode a different URL or customize the QR code's appearance by adjusting the settings in the script.

## License

This project is licensed under the [MIT License](LICENSE).
