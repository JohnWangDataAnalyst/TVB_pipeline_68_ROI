#This is a TVB preprocessing pipeline with two choices of ROI 68 and 96 region


#Firstly, get python3.3 on the cluster by  
source /opt/source/python3.3.sh

#pull this repo to a directory make sure GUI_wz_m.py are in the same directory as TVB folder.

#Then, you are able to use GUI to setup working directory, data directory structure and enviornment variables you need to call Freesurfer, Mtrix and Matlab and used as public variables in the scripts such as subID.  
Also GUI help you copy data and scripts you need to run.

python GUI_wz_m.py
# input data files directory and working directory
  the number of ROI
  subject ID
  and choose sub-processing

  press button diretory processing
  press button copy data
  press button set environment variables
  press button creat shell script 
you can skip directory processing and copy data buttons as long you get data ready at your working directory
but you have give subject ID, number of ROI and working directory to setup variables and pick sub-processing. 

You are ready to go!



