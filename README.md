## HandDrawnImageRecoginition
The project consists of two parts.  
- Training the model 
- Interative visualization of results  

#### Traing the model: 
Model takes in 10 classes as input.  
The following are the 10 classes: 
[['alarm_clock', 'tennis_racquet', 'cloud', 'eye', 'sword', 'book', 'laptop', 'star','spoon', 'coffee_cup' ]  
Model is trained using the nparray dataset downloaded from Google Quick Draw Dataset Model is a Simple CNN.  
Trained Model is now converted to a Tensorflowjs model. 

#### Interactive Visualization of results:
An app is developed: to detect the results.  
Javascript is used to for a interactive canvas image to be drawn and the results are posted right after detection.   

#### Steps to run the project:  
1. Download WebPage_Model.zip 
2. Create an environments with all the dependencies installed from all_requirements.txt 
3. This code already contains a trained model which is converted to tensorflowjs 
4. Now from the environment, run app.py. It should run the webpage on the localhost:5000 
5. If it doesn't access the file.    

#### Run the whole training dataset too:  
1. Create an environment for the project to be run 
2. Install all the requirements from all_requirements.txt 
3. Run the ML_Code.ipynb file 
4. I am trying to convert the model to a tensorflowjs, it wasn't working on my machine. So I have converted it on Google Colab. 
5. Download the webpage folder and unzip it. 
6. Now from the environment, run app.py in the unzipped folder file  
7. Access: localhost:5000 8. 
Play with the program
