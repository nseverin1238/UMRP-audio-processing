# UMRP-audio-processing
This repository contains code for preparing the URMP dataset. Follow the steps below to get
project working on your machine.

## Set up the project folder
Git clone the project.

## Virtual environment  
Next, set up the virtual environment. 

On Windows or Linux, execute: 

```bash 
python3 -m venv env
```

Next, to activate virtual environment:

- On Windows

```bash
env\Scripts\activate.bat
```
- On Linux
```bash
source env/bin/activate
```

On Windows execute: 


## Install dependencies
Currently, you need to install the following dependencies.

- librosa
- matplotlib 
- numpy
- opencv-python

To install the above, execute the following: 

```sbash 
pip install -r requirements.txt
```

Furthermore, you'll need install ffmpeg from source code to get the project going.

## Setting up project folder
Copy the URMP data set folder into the project folder and name it URMP.

## Preparing dataset 
Finally, execute: 

```bash 
python generate_annotations.py 
```
