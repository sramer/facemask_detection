Steps to run FaceMask app::

1. Getting Started: #############################################################

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
