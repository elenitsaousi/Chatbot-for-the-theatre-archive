# TheatreProject
This project use  open source bot framework Rasa. Is about a project-workshop in Athena center.


For this project you have to create a conda enviroment, and download sqlite,rasa 3.1 and python 3.7.
## Download what it needs
    conda create -n myenv python=3.7
    
    conda activate myenv

    pip3 install rasa==3.1

    conda install -c anaconda sqlite

    pip install pandas

## To run this project you have to run the follow cmds
    rasa train 
    rasa run actions  
        and at the same time
    rasa run -m models --enable-api --cors "*"
 
 
    
