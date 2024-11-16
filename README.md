GestureFlow - 
This Python-based project enables interactive control of presentation slides through hand gestures captured via a webcam. Using OpenCV and CVZone libraries, the application recognizes specific gestures to navigate slides and perform annotations in real-time. It's designed to provide an engaging and hands-free experience for presentations.

Description - 
The project offers an intuitive interface, allowing users to control presentation slides through recognized hand gestures captured in real-time via a webcam. With this system, presenters can effortlessly transition between slides, draw annotations, and use their finger as a pointer during presentations.

Key Features - 
Gesture Control - Navigate slides with left and right hand gestures, mimicking page flipping for seamless transitions.

Annotation - Draw on slides using hand gestures, enabling on-the-fly illustrations or emphasis during presentations.

Pointer Mode - Use the index finger as a virtual pointer, enhancing interaction and engagement with specific elements on slides.

Clear Annotations - Instantly clear drawn annotations with a specific gesture, ensuring a clean canvas for further interactions.

Technologies Used - 
Python : The project's core language for developing the application's functionalities and logic.
OpenCV (cv2) : Handles webcam access, image manipulation, and gesture recognition to control slide navigation and annotations.
NumPy : Assists in efficient handling and manipulation of image data for gesture recognition and processing.
CVZone : Provides specialized tools and functions for precise hand tracking and gesture-based interactions within the presentation slides.

Requirements -

Python 3.x
Webcam

Configurations -

Adjust webcam resolution via width and height variables.
Modify FolderPath to the directory containing presentation slides in main.py file.
Fine-tune gestureThreshold, button_delay, and other parameters as needed.
