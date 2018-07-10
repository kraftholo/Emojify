# Emojify

This App makes use of the phone's camera and takes a picture. It then detects the number of faces by making use of the Google Mobile Vision Api (specifically the com.google.android.gms.vision.face FaceDetector subpackage). Using a FaceDetectorit classifies the face and gives us the probabilities of -
-left or right eye being closed
-whether the person is smiling or not
These probabilities are then matched to the corresponding BitEmoji ,which is then combined with the original image and then returned in an imageView.
The returned image may then be shared or saved.

