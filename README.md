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

