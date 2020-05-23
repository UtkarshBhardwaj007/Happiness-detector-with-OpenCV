# Happiness-detector-with-OpenCV
Detect whether a person is smiling and also the face and the eyes using haar cascades.

This is an implementation of the viola - jones algorithm. Using OpenCV the results are obtained in real time. However the results are not as accurate as a SSD.

The accuracy can be changed by tweaking the scaleFactor (second argument of detectMultiScale function) and minNeighbors (third argument of detectMultiScale function). The values in the provided code have been achieved by experimenting.
