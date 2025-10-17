# Tracknet_Tennis_project
Tracknet is a deep learning model used for tracking small, fast-moving objects with high accuracy. Not only does Tracknet locate a ball in a frame, but using pattern recognition it can predict its flight motion. Tracknet can be applied with post game analysis and research collecting, ex:player shot selection and positioning.

A csv file accompanies the images which contains frame, ball visibility (represented 0-3), x coordinate for center of bounding box, y coordinate for center of bounding box, and the status of the ball (fly, hit, bounce). The model used in this project is trained with a 19,835 frame dataset. 

# Code
tracknet_tennis_project.py contains the Python code used to convert a normal broadcasted tennis clip into one which tracks ball movement, the players, and the court. Process can be repeated with any high quality, standard broadcast tennis clip.

## Acknowledgements

This project builds upon the work from (https://github.com/yastrebksv/TrackNet).


