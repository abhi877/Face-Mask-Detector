# Face-Mask-Detector
The purpose of implementing the Face Mask Detector application is to first detect different faces and then recognise the masks on different faces.
The two approaches that I followed to initiate this project is:
1) Detection technique to detect whether there is a face present or not.
2) Recognition technique to recognize whether the face wearing a mask or not.

This particular application is based on two phases: firstly, Training phase followed by Inference phase.

Training phase:
--------------
The purpose of Training phase is to create a detectable windows to recognize whether the face is present in the windows or not. 
It creates a window with the help of co-ordinates (x, y, w, h) and recognize the co-ordinates to detect the face in the window.
The first process of Training phase is to make the dataset with the collection of various faces and then execute the code on these faces to detect whether there is a mask on the face or not. The classification of mask present on the face or not would be recognized by binary classification. (0 for non-mask and 1 for mask)

Inference Phase:
----------------
In inference phase,
Firstly, we create a frame to detect the exact co-ordinates of the face so that we can recognize the face present in the window or not. Secondly, we do some scaling to make the face visible by the window and it pour down to 80% means the compiler will detect the face present in the window by pour down to 80%. Furthermore, we detect the face with the help of co-orrdinates (x, y, w, h) by executing the code every time it detects the new face.

Technology Used:
----------------
I used python language to implement this project and some algorithms of Machine Learning to recognize the masks on the faces of different inputs. I divided this project in two phases: Training phase and Inference phase. In Training phase, I used Python to detect the windows whether the face is present or not by detecting the co-ordinates of the face. 
In inference phase, I used some algorithms of Machine Language to create the co-ordinates of the face through we can detect the presence of mask. To implement the python language, I used the eclipse platform.

My role:
--------
This is an individual project and is created by myself. I divided the whole program into number of modules(functions) that are being made in Python language. Each module of this program has its own significance and used to detect the face mask. 

Hardships:
----------
To implement the Training phase, I did not face so much difficulties to implement it because there are some in-built libraries in python that one can directly use to invoke some pre-defined functions to detect theco-ordinates of the face. 
To implement the Inference phase, I had some hardhips to create the co-ordinate of the face where a mask can be put on. I used some algorithms of Machine Learning such as Baysian algorithm to create the detectable points on the face but could not able to implement it properly.
Overall, the implementation of python was quite easy because of the in-built libraries but I find difficulty to implement the Baysian Algorithm to create the co-ordinates of the face. 
Right now, I am getting the theoretical and practical approach of the Baysian algorithm to create the detectable points. 

