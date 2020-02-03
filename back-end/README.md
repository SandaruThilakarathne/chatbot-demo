# JSONFilter

##### Author:
    Theekshana Sandaru Thilakarathne

## Step 0
Follow these only if you don't have python 3x, pip, virtualenv and virtualenvwrapper installed in your machine.
If you do, then skip to step 1
#### a) Install python 3x
    
    1) For Ubuntu / Linux OS
        1. verify using 'python --version'
        
        if python 3.x there move to the step 1
        
        2. sudo apt update
        
        3. sudo apt install software-properties-common
        
        4. sudo add-apt-repository ppa:deadsnakes/ppa
        
        5. sudo apt update
        
        6. sudo apt install python3.7
        
        7. check python version to verify the installation using 'python ––version'
    
    2) For Windows
        1. verify using 'python --version'
        
        2. downlaod the python 3.7 using below link and install: -
           https://www.python.org/downloads/
           
        3. check python version to verify the installation using 'python ––version'
 
#### b) Install pip
    
    1) For Ubuntu / Linux OS
	    1. verify using 'pip --version'
	    
	    2. sudo apt update
	    
	    3. sudo apt install python3-pip
	    
	    4. verify the pip version to confirm

    2) For Windows
        
        1. verify using 'pip --version'
        
        if not available follow the steps
        
        2. python3 get-pip.py


## Step 1
#### 1) Install virtualenv library
      1. For Ubuntu / Linux OS
            sudo pip3 install virtualenv 
      
      2. For Windows OS
            pip3 install virtualenv 

#### 2) Install virtualenvwrapper library
      1. For Ubuntu / Linux OS
            sudo pip3 install virtualenvwrapper
      
      2. For Windows OS
            pip3 install virtualenvwrapper
            
## Step 2
#### 1) Create a virtual environment

    1. For Ubuntu / Linux OS
        In command shell; Go to project's root directory and create a virtual environment.
        
        1. sudo apt-get update
        
        2. virtualenv -p python3 venv
     
    2. For Windows OS
    
        In command shell; Go to project's root directory and create a virtual environment.
        eg : virtualenv venv
        (This creates the 'venv' folder inside Project's root directory)

#### 2) To activate the virtual environment
    
    1. For Ubuntu / Linux OS
        . venv/bin/activate
        
        (when you need to deactivate run command 'deactivate')
        
    2. For Windows OS
        In command shell; Go to project's root directory
        run command 'venv\Scripts\activate'
    
        (when you need to deactivate run command 'deactivate')

## Step 03
#### 1) Installing requirements.txt
        
        1. For Ubuntu / Linux
            sudo pip3 install -r requirements.txt
        
        2. For Windows OS
            pip3 install -r requirements.txt


## Step 04
#### Setup FLASK_ENV and FLASK_APP

       In both OS after activating the virtual environment you can run below command
       
       FLASK_APP=app.py
       FLASK_ENV=development
       
       add your google credentials in to cred directory
       
       then to start run `python app.py`

## Step 05
#### For local development ngrok make tunnel
    1. Download ngrok from below link
        https://ngrok.com/download
    
    2. cd <path_to_ngrok> 
    
    3. ./ngrok <PORT YOU GOING TO START THE APP>


## Step 06
#### Dialog Flow
    
    1. Once tunnel open go to the dialogflow site and the fullfillment tab
    
    2. Enable webhook
    
    3. Place the url path for your tunnel
     
    
                 