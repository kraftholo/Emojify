# Emojify

This App makes use of the phone's camera and takes a picture. It then detects the number of faces by making use of the Google Mobile Vision library (specifically the com.google.android.gms.vision.face FaceDetector subpackage). Using a FaceDetectorit classifies the face and gives us the probabilities of -
-left or right eye being closed
-whether the person is smiling or not
These probabilities are then matched to the corresponding BitEmoji ,which is then combined with the original image and then returned in an imageView.
The returned image may then be shared or saved.

-Additionally the ButterKnife and Timber libraries have been used.

SCREENSHOTS

https://github.com/kraftholo/Emojify/blob/master/JPEG_20180710_132529.jpg
https://github.com/kraftholo/Emojify/blob/master/JPEG_20180710_132646.jpg
https://github.com/kraftholo/Emojify/blob/master/Screenshot_20180710-142818.jpg
https://github.com/kraftholo/Emojify/blob/master/Screenshot_20180710-142838.jpg
