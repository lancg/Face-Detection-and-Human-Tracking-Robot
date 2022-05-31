# Face-Detection-and-Human-Tracking-Robot
MathWorks' project in 2022
facedetection_demp.slx is the face detection algorithm given in the reference document. 
facedetection_raspi.slx is the motion control program which should be set in Raspberry Pi.   
what‘s more，we also design a voice controlled program and GPS path navigation and path acquisition（based on Matlab Mobile）.  
We try to deployer voice controlled program by the same way as face detection in Android,but it works bad,nearly always display that noise is too loud.We guess there may be a problem with the device microphone
Unfortunately，two of our team members（3 guys total）are iPhone users，so we can just finish it with PC.  
And all these control modes can complete the control of the trolley through UDP.
