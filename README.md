# SYMFesizer
## Project Setting
The following exam project explains the implementation of an 'Air Guitar' system, which creates an acoustic guitar in air.

Through the use of the KINECT sensor, it is possible to scan the human body and thanks to the recognition of particular movements, it is possible to recreate sounds without the use of a real, physical instrument. 
Specifically, what has been implemented uses only the movement of the right hand. For it, movement is traced along the vertical y-axis and along the x-axis. For the first movement, a real strumming is traced, which is affected by the speed of the movement, while for the second, movement along the x-axis is traced, which affects the intensity of the sound. In fact, trying to simulate a real system, playing towards the right, i.e. towards the bridge of the acoustic guitar will produce a lower intensity of sound, while vice versa, playing towards the left, near the neck, will produce a sound of greater intensity. 
