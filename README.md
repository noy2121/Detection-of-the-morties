# Detection-of-the-morties
Small scale detection model. Using pre-trained RetinaNet we can now detect morties. 
We set the threshold to be 0.8.
Using SGD we achieved loss of 0.0003.
Most of the morties successfully detected. We achieved accuracy of 88% (only 2 out of 16 didn't detected)
Nevertheless, the model detect other objects as morties, means the model precision is low.
We can add more training data to solve this issue.
