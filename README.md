Image Steganography Application
A modern GUI application for hiding secret messages within images using steganography techniques. Built with Python and Tkinter.

Check out project Screenshots here

Features
🖼️ Support for multiple image formats (PNG, JPG, BMP)
📝 Text input directly or from files
🔐 Password protection for message encoding/decoding
🎨 Modern dark-themed GUI interface
📊 Real-time status updates
⚡ Fast encoding and decoding
💾 Save encoded images in high-quality PNG format
Installation
Clone the repository:
git clone  https://github.com/SuyashBharte/aicte_intern_project.git
Install the required dependencies:
pip install -r requirements.txt
Usage
Run the application:
python steganography_app.py
To encode a message:

Click "Select Image" to choose your carrier image
Enter your secret message or use "Load from File" to load from a text file
Enter a password for security
Click "Encode Message"
Choose where to save the encoded image
To decode a message:

Select the encoded image
Enter the password used during encoding
Click "Decode Message"
The hidden message will appear in the output section
Technical Details
The application uses the following techniques:

LSB (Least Significant Bit) steganography
Password-based message protection
Custom pixel manipulation using OpenCV
Message length preservation in image metadata
Requirements
Python 3.8+
OpenCV (opencv-python)
Pillow
NumPy
Tkinter (included with Python)

Acknowledgments
Thanks to the OpenCV team for their amazing image processing library
Inspired by various steganography techniques and implementations
Security Note
This implementation is for educational purposes. For sensitive data, please use established encryption standards and it is developed with Automated GPT (Claude Sonet 3.5).

Author
Suyash Bharte - https://github.com/SuyashBharte/aicte_intern_project.git


Support
If you found this project helpful, please give it a ⭐️!
