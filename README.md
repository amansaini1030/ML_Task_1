ML_Task_1 :-

First of all lets generate the Dataset for face Recognition

1.) ML_Task_Dataset

    # Before generating the dataset :
      - Create Two Folders with name shown inside the dataset folder --> train & validation 
      - Inside train & validation folder create a different folder for each face.
      - Our dataset will look like : 
        dataset:
          1.) train :
              1.) face1
              2.) face2
          2.) validation :
              1.) face1
              2.) face2
    Now for generating the dataset for different faces you can use ML_Task_Dataset program file for :
    # Generation of dataset for our face Recognition
    
    After generating the dataset for 1 face :
      - Copy 75-80% of the image files generated from dataset genrated in /train/face1/
      - Similarly copy rest of the data in the /validation/face1/

After generating the dataset for all the faces you can use ML_Task_Traing program file for traing the model
Note:- Here I have created this program file for training of Two face Recognition

2.) ML_Task_Training
    # Using VGG for creating our own FaceRocognition model
    # Funtion to add new layers to the model
    # modelnew created
    # Loading our dataset for face recognition
    # Training out the Model
    
After Training you can use ML_Task_Testing program file to test the accuracy of newmodel created

3.) ML_Task_Testing
    # Testing of the FaceRecognition Model
