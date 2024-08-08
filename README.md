# Vehicle-Classification


You can use AI program to fulfill the type of transport.

![add image descrition here](direct image link here)







## The Algorithm
It takes a photo of a transport that yoi give it, and detects what kind of transport it is. It detects several types of transport:
Bus
Motorcycle
Truck
Car

## Running this project
Running this project
1. Setup your Jetson Nano and Install VScode
2. Connect Jetson Nano onto your computer hotspot. Write down your Jetson Nano IP address for later use
3. Connect your VScode to your Jetson Nano using Connect Host and ssh nvidia@|PAddress
4. Open the NVIDIA home folder
﻿﻿﻿5. Open the terminal and use cd jetson-inference/python/training/classification to enter the needed directory
6. ﻿﻿﻿Use NET=models/Vehicle and DATASET=data/Vehicle to set NET and DATASET for later reference
7. ﻿﻿﻿Select a photo in the test folder
﻿﻿﻿8. Run the model using imagenet.py -model=SNET/resnet18.onx -input_blob-input_ 0 output_ blob-output_0 -labels-SDATASET/labels. txt $DATASET/test/
IMAGE_NAME.jpg OUTPUTNAME.jpg Replace IMAGE_NAME and OUTPUTNAME with your photo names
9. Enjoy running the Vehicle detector!

[View a video explanation here](video link)
