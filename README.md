# Image Steganography using Digital Signal Processing 🖼️🔐

## Overview
This project demonstrates **Image Steganography** techniques using **Digital Signal Processing (DSP)** to securely hide text within images. The implementation focuses on secure data hiding and extraction, enhancing privacy in digital communication.

## Features ✨
- **Text Concealment within Images** 🖋️
- **Secure Data Hiding & Extraction Algorithms** 🔐
- **Least Significant Bit (LSB) Encoding Technique** 📊
- **Support for Multiple Image Formats** 🖼️
- **Cryptography Integration for Enhanced Security** 🔑

## Project Structure 📂
```
📁 Image-Steganography
│── Steganography.py                # Main Python script for encoding & decoding
│── cat.jpg                          # Sample cover image
│── hidden.png                        # Image with hidden text
│── logo.jpg                          # Additional test image
│── logo.png                          # Additional test image
│── 2021ImageandaudiosteganographybasedonindirectLSB.pdf # Research paper
│── README.md                         # Project documentation
```

## Installation & Setup ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Image-Steganography.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script:
   ```bash
   python Steganography.py
   ```

## Usage 🚀
1. **Hide a message in an image:**
   - Run `Steganography.py` and choose the encode option.
   - Select an image and enter the secret message.
   - The encoded image will be saved as `hidden.png`.

2. **Extract a hidden message:**
   - Run `Steganography.py` and choose the decode option.
   - Select the encoded image.
   - The hidden message will be displayed.

## Live Demo 🎥
![Steganography Process](hidden.png)

## Contributions 🤝
Feel free to fork the repository, submit issues, or contribute improvements to enhance security and efficiency.

---


