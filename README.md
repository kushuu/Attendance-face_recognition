# attendance-face_recognition

- So this is a fairly simple openCV project in which I've tried to mark the attendance of people whose faces are recognized in the frame.
- Live video is taken as an input to the script, which is then worked upon.
- Facial recognition is done using the face_recognition package of python.
- The encodings of the face in the frame is matched with every face in the photos' directory.
- The face which matches the most among all the faces, its filename is used to make an entry in the csv file.
- The csv file made also has the time at which the face was detected.
- A folder named "ImageAttendance" which had all the photos, has been removed from this repo for privacy concerns.
