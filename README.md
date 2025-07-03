# image-Encryption-Tool-Report.-

Simple Image Encryption Tool

Overview

This is a beginner-friendly Image Encryption and Decryption Tool built with Python using basic pixel manipulation techniques. It allows users to encrypt and decrypt images by modifying pixel values or swapping pixel positions.

Features

Pixel value modification using a simple mathematical operation (addition modulo 256).

Optional pixel swapping (flip or reverse).

Easy encryption and decryption process.

Technologies Used

Python 3

OpenCV (cv2)

NumPy

How to Run 🚀

Prerequisites:

Python installed

Required libraries:

pip install opencv-python numpy matplotlib

Steps:

Clone this repository or copy the code.

Place an image (e.g., sample_image.jpg) in the same directory.

Run the code in Jupyter Notebook, Google Colab, or any Python IDE.

Example Usage:

encrypted_img = encrypt_image('sample_image.jpg', key=100)
decrypted_img = decrypt_image(encrypted_img, key=100)

Applications

Basic image obfuscation

Educational cryptography demonstrations

Lightweight image protection

Limitations 

This is not suitable for securing sensitive data.

It is intended for learning purposes only.

Author

Harshitha

License 📄

This project is licensed under the MIT License.


