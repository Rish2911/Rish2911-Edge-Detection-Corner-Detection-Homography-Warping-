Just copy and paste all the files in a folder (including the videos)
For running all the codes you need to create an environment first and then install the libraries. 
Install required packages onto your virtual environment. Replace “myenv”with your environment name. 
Enter the following commands in your terminal window. Press ‘y’ when prompted. 
a. conda create -n myenv python=3.7
b. conda activate myenv
c. conda install -c conda-forge opencv=4.1.0
d. conda install -c anaconda numpy
e. conda install -c conda-forge matplotlib
f. conda install -c conda-forge imutils
g. (optional) conda install spyder=4.2.0
h. (optional) spyder
i. pip3 install sympy 

After installing all the libraries, we are ready to run the codes. All the codes are in jupyter notebook format
q2 is for problem 2, which requires the video file. Keep the files in the same location as where the code files and your environment is (or else change the path in the below line in the codes accordingly)
cap = cv2.VideoCapture('tag.mp4')
Just press shifter enter to run each cell individually or elese run all the cells from the editor menu. Or else type 'python3 file_name.py' by going to the file location in the terminal.

Keep the testudo image also in the same folder as the jupyter files are

