# Steps to run FaceMask app::

1 -> After downloading the FaceMask directory navigate to the director using cmd. 

> cd FaceMask

2 -> Create a Virtual Environment using Virtualenv

    - Download the virtualenv using the following command if not exits:
      Note: Leave the below the step if virtualenv already exists in you pc.

          > python -m pip install --user virtualenv
    
    - After installing the virtualenv in your pc create a virtual environment in the project folder.

           $ FaceMask > python -m venv env
           $ FaceMask > env\Scripts\activate.bat // To activate venv
    

    - Now run the following code to install the required libraries

            > pip install -r requirements.txt


2. Working with the app

-> run the below command in the terminal to train the dataset
        
        > python train_mask_detector.py --dataset dataset

-> To detect face in an image run the below command

        > python detect_mask_image.py --image images/pic1.jpeg

-> To detect face in a video run the below command

        > python detect_mask_video.py
        

#######################################################################################

# Advantages of Face Mask Detection System:
1. Face mask detection platform can quickly identify the person with a mask, using cameras and analytics.
2. Identify faces, including facial features through technology, especially hardware, like video cameras.
3. Enhance surveilance systems.
4. Identify people without masks by generating an alarm or a notification to notify security or officials
5. Provides a way to prevent the spread of dangerous viruses like COVID-19.

# Future enhancements:
1. The system is easy to implement in any existing organizational system. 
2. Custom alerts can be sent to the person with or without a face mask or the one whose face is unrecognizable in the admin system.
3. No need to install any hardware as the system can be connected with your existing surveillance system only.
4. The system can be used easily with any camera or hardware like surveillance cameras.
5. The system restricts access for those not wearing the masks and notifies the authorities.
6. You can customize the face mask detection system based on your business requirements. 
7. You can check the analytics based on the system generated reports. 
8. Easy to access and control the movements from any device through face mask detection applications. 
        
       
