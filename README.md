# face_recognition_attendance
In this project students or anyone can give attendance of presence by facial recognition.
Face Recognition Attendance System
This Python script uses face recognition to identify individuals in a video feed and keeps track of their attendance. The script uses the OpenCV and face_recognition libraries to detect faces in the video feed and compare them to known faces stored in the script. When a known face is detected, the script records the time the individual was present in a CSV file.

Installation
Clone or download the repository to your local machine.
Install the necessary Python packages by running pip install -r requirements.txt in your terminal or command prompt.
Add images of individuals you wish to detect in the Faces directory.
Update the known_face_encodings and known_face_names arrays in the script with the face encodings and names of the individuals you wish to detect.
Usage
In your terminal or command prompt, navigate to the directory containing the script.
Run the script by entering python attendance.py in your terminal or command prompt.
A live video feed will open, and the script will begin detecting faces in the video feed.
When a known face is detected, the script will mark the individual as present and record the time they were present in a CSV file.
Press 'q' to exit the script and close the video feed.
Contributing
If you'd like to contribute to this project, please fork the repository and make your changes in a new branch. Once you've made your changes, submit a pull request explaining the changes you've made and why they're valuable.

License
This code is available under the MIT License.
