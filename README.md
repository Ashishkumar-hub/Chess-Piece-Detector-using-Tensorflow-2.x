# Chess Piece Detector 

This is an end to end Chess Pieces Object detection Project where the pieces in the chess are identified as pawn, king, knight etc.

#### About the Datatset

    I have collected this dataset from Roboflow. The dataset is of Chess board photos and various pieces. 
    All photos were captured from a constant angle, a tripod to the left of the board. The bounding boxes of 
    all pieces are annotated as follows: white-king, white-queen, white-bishop, white-knight, white-rook, 
    white-pawn, black-king, black-queen, black-bishop, black-knight, black-rook, black-pawn. 
    There are 2894 labels across 292 images. 
    
[Link to dataset - Click Here](https://public.roboflow.com/object-detection/chess-full)

#### For Running the Project:

    I have used Tensorflow 2.x for object detection. 
    Kindly visit the official reporsitory for tensorflow and download the models folder for running the project 
    you just need few folders from the reserch folders copy those and keep them in the extracted folder for this
    repository. Your directory should be loooking like below image.
    
 ![Capture](https://user-images.githubusercontent.com/55132850/155108555-133f5263-e013-45c0-8731-2548489e0101.PNG)
    
    Now for downloading the custom model trained kindly visit the below link and download the custom model trained 
    and then paste that folder in same directory. 
    
 [Link to custom trained my_model folder - Click Here](https://drive.google.com/file/d/1WhtxR50-3y8haDusbd2oJB4F7KsmEJdS/view?usp=sharing)
 
    > Open the project in Pychram or VS code 

    > Create a new Conda environemnt 
    - File > Settings > Python Interpretor > Add > #### Results:Create new conda environment
    
    > Activate the enviironment in terminal conda activate "ENV_NAME" 

    > Run : pip install - requirements.txt

    > Run the project find it on http://127.0.0.1:8000/

    > Kindly use some of the images in sample images folder for testing it or you can see the SS below.

#### Results:

    This is how your web application will look. Just cick on upload and upload the image from sample images folder 
    and click on predict to see the results. 

Step 1 : Click on Upload and choose the image.

![Screenshot (302)](https://user-images.githubusercontent.com/55132850/155110176-a31b3c73-bfb2-40ee-af26-aecf6ca9ae90.png)

Step 2 : Now Click on Predict to perform the object detection using the custom model created. 

![Screenshot (303)](https://user-images.githubusercontent.com/55132850/155110181-3d5dcc71-e8ef-4446-8046-9b2cb260ca85.png)

Step :3 Your Results will be shown lik ebelow. It will also be saved in the saem older in your directory.

![Screenshot (304)](https://user-images.githubusercontent.com/55132850/155110160-f2f3b660-053b-49ce-8500-5ac90a0b3834.png)

   
