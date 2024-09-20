# Signature Authentication System
Welcome to the Signature Authentication System! This Python-based application allows you to compare two signatures to verify their authenticity. Whether you’re working with scanned images or live webcam captures, this tool can help you quickly and easily determine if two signatures match.

## Features
Capture signatures using a webcam: No scanner? No problem! Just sign on a piece of paper, and this app will capture it through your webcam.
Upload signature images: You can upload images of signatures in .jpeg, .png, or .jpg format.
Signature comparison: Compare two signatures based on a custom matching algorithm.
User-friendly interface: Built with Tkinter, this app is easy to use and provides instant feedback on whether the signatures match.
## How It Works
Capture or upload two signatures.
The app compares them using a custom signature matching algorithm.
If the similarity between the two signatures exceeds a certain threshold (85%), they are considered a match.
## Technologies Used
Python
Tkinter for the graphical user interface (GUI).
OpenCV for capturing images from the webcam and handling image processing.
Custom Signature Matching algorithm (you’ll need to add this to the signature.py file).
Installation
Prerequisites
You need Python installed on your machine. Download it from here.
Make sure you have the following Python packages installed:
Tkinter (comes pre-installed with Python)
OpenCV: You can install it using pip:
bash
Copy code
pip install opencv-python
NumPy (just in case it's used in the matching logic):
bash
Copy code
pip install numpy
Clone the Repository
First, clone the repository to your local machine:

bash
Copy code
git clone https://github.com/YourUsername/Signature-Authentication.git
Running the Application
Navigate to the project directory:

bash
Copy code
cd Signature-Authentication
Run the Python script:

bash
Copy code
python signature_authentication.py
How to Use
Launch the app: When the GUI window opens, you’ll see options to upload or capture two signature images.

Upload or capture signatures:

To capture a signature, click the "Capture" button. Use your webcam to capture an image of your signature.
To upload a signature, click the "Browse" button and select an image file.
Compare signatures: After both signatures are ready, click the "Compare" button. The app will compare the signatures and display whether they match or not.


To-Do
Implement the signature matching algorithm in signature.py.
Improve error handling (e.g., handling camera errors or invalid file formats).
Add more documentation for contributors.
Contribution
Want to improve this project? Feel free to fork this repository, submit pull requests, or open issues. All contributions are welcome!

License
This project is open source and available under the MIT License.

Contact
If you have any questions or feedback, feel free to reach out to me at Ansharabeigh@gmail.com.
