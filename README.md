# Face-Detection-and-Human-Tracking-Robot
MathWorks' project in 2022
facedetection_demp.slx is the face detection algorithm given in the reference document. 
facedetection_raspi.slx is the motion control program which should be set in Raspberry Pi.  
voice_detection_m read the microphone voice, separate it by convolution neural network according to the sound spectrum diagram, and get the recognized different instruction words. According to the obtained instructions, send the control signal to raspberry pie through UDP.  
helperExtractAuditoryFeatures.m convert the audio signal into frequency spectrum information for subsequent identification, which is recognized by voice_ detection.m call.  
GPS_sport.m using GPS Using GPS signal to control trolley movement（As the environment is often complex，it may work not well）（to fit the environment we test，we have debugged for a long time）
Kalman_locus.m: Using Kalman filter to display trajectory.  
what‘s more，we also design a voice controlled program and GPS path navigation and path acquisition（based on Matlab Mobile）.  
We try to deployer voice controlled program by the same way as face detection in Android,but it works bad,nearly always display that noise is too loud.We guess there may be a problem with the device microphone
Unfortunately，two of our team members（3 guys total）are iPhone users，so we can just finish it with PC.  
And all these control modes can complete the control of the trolley through UDP.  
our video can be see in [video](https://jbox.sjtu.edu.cn/l/a1SBSi).  

I'm sorry that you may can't see the video above.Now I have submitted it here [video_clip](https://github.com/lancg/Face-Detection-and-Human-Tracking-Robot/blob/0f6801a00d706ab8352d62e2c8982df95976f72b/test_success_clip.MP4)）.But it's too big to add in github,so I have to edit it(mainly GPS sport as we have to let it sport for a long time so that we can see the change of coordinates,it costs a lot).The old link still provides original video without cutting. 

Thank you for reading! 
