# Photo-Attendance-Exercise
Exercise on using OpenCV to match a given reference image with a set of test images

<br> The approach I have used involves using the ORB algorithm for feature matching
<br> I have used 10 test images of unique people as my test dataset
<br> I have 2 reference images, one a positive testcase (11.pgm) and another a negative testcase (12.pgm)
<br> 11.pgm shows up a match with 8.pgm, as can be verified using the images, they are of the same person
<br> 12.pgm shows no match since it doesn't belong in the test dataset
