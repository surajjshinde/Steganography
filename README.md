# Steganography
Hide and reveal secret messages in images

Overview:
This is a GUI-based steganography tool that allows users to hide and retrieve secret text messages in image files using the Least Significant Bit (LSB) technique. The application is built using Python and Tkinter, with image processing handled by PIL (Pillow) and steganographic functions provided by stegano.

Features:
- Load an image file (PNG, JPG).
- Hide a secret message inside an image.
- Reveal hidden text from a steganographic image.
- Save the modified image with the hidden message.
- Simple and user-friendly graphical interface.

Installation & Setup:
Prerequisites:
Ensure you have Python installed (version 3.x recommended). Install the required dependencies using:

```sh
pip install tkinter pillow stegano
```

Running the Application:
1. Download or clone this repository.
2. Navigate to the project directory.
3. Run the script using:
   ```sh
   python main.py
   ```

How to Use:
1. Open an Image:
- Click the Open Image button.
- Select an image file (PNG, JPG).
- The image will be displayed in the interface.

2. Hide a Message:
- Type a secret message in the text area.
- Click the Hide Data button.
- The message will be embedded into the selected image.

Save the Image:
- Click the Save Image button.
- The modified image (with the hidden message) will be saved as `hidden.png`.

Retrieve Hidden Message:
- Click the Show Data button.
- The hidden message will be extracted and displayed in the text area.

Project Structure:
```
/Steganography-Tool
│── main.py             # Main application script
│── logo.png            # Logo used in GUI
│── hidden.png          # Output image with hidden text (generated)
│── README.md           # Project documentation
```

Libraries Used:
- `tkinter` → GUI framework
- `PIL (Pillow)` → Image processing
- `stegano` → Steganography library for hiding/revealing text in images

Future Enhancements:
- Support for more image formats (JPEG, BMP).
- Encryption for added security.
- Drag-and-drop support for image selection.
