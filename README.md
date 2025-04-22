# Criminal-face-detection
Implemented using:

 


Do remember to star ⭐ the repository if you like what you see!

Star Badge GitHub stars


explain


Introduction 🌟
Welcome to a customizable face recognition system designed to identify individuals in photographs based on a user-populated database of facial images. This powerful tool harnesses Python and its potent libraries, such as face_recognition and opencv, offering a blend of accuracy and user-centric functionality. Tailor the database with your images and let the system pinpoint matches with ease.


Features 🚀
Face Detection: Utilizes Haar Cascade classifiers to detect faces within images. 🔎
Face Recognition: Matches detected faces against a pre-established database to identify individuals. 👤
Annotation: Labels recognized faces with rectangles and their corresponding names. 🏷️
Scalability: Designed with future enhancements in mind, including video file processing. 📈

Installation 💻
Ensure you have Python installed, and then set up the required libraries with the following commands:

pip install face_recognition opencv-python
Get the code by cloning this repository:

git clone https://github.com/your-github-username/face-recognition-system.git

Usage 📘
Prepare a database directory containing named images of individuals.
Execute the script.
Select an image through the file dialog prompt.
Let the system work its magic, detecting, recognizing, and annotating faces, saving the output as result.jpg.
Running the Script
Navigate to the script's directory and run:

python main.py

Database Structure 🗂️
The database should meet the following criteria:

Only image formats such as .png, .jpg, .jpeg, .tiff, .bmp, or .gif.
Each image should display only one individual's face.
Image filenames should correspond to the individual's name.

Output 🖼️
The processed image will be stored as result.jpg in the project's root directory, complete with labeled rectangles around each recognized face.


Contributions 👐
Your contributions are welcome! If you have suggestions for improvements, please open an issue to kick off the discussion.


Future Updates 🔄
Here's what's on the horizon for this face recognition system:

Video Processing: We plan to extend the system's capabilities to detect and recognize faces in video files, enhancing its applicability in various real-world scenarios.
Real-Time Recognition: Implementing the ability to recognize faces in real-time through live video feeds.
Stay tuned for these exciting enhancements that will make the system more powerful and versatile for all users!


Acknowledgments 👏
Props to Haar Cascades for the face detection capabilities. Gratitude to the face_recognition library for simplifying facial recognition technology. Kudos to opencv and matplotlib for their powerful image processing and visualization tools.


Do remember to star ⭐ the repository if you like what you see!
