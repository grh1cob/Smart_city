# Smart_city
please open below mentioned link to see project files
https://drive.google.com/drive/folders/1ErzHsXD22_MkNjb2MCARGJkB5CJxxpPd
The above mentioned link contains two folders, one containing a semantic segmentation model trained for detecting potholes. It contains an internal readme file , which has instructions for executing it.
The input picture is there in the pspnet folder named as pothole.jpg, and the output image of the semantic segmentation on Indian roads is present in link given above.
The smartcity folder contains yolo version2 network trained to count passing vehicles.
Instructions:
Install Anaconda python3
Install tensorflow (if gpu is required install the corresponding cuda and cuddn files)
Install opencv
and run the command
pip install -r requirements.txt
To install other necessory libraries.
The project is packaged as django server
To run the server run the command
python manage.py runserver
