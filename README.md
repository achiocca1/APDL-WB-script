# APDL-WB-sequential-script-running
This script is useful to start a sequence of APDL scripts in Workbench and solve them one by one automatically.<br/>
<br/>
###########################################################################<br/>
######################## HOW TO USE THE SCRIPT ############################<br/>
###########################################################################<br/>
<br/>
Run a series of APDL scripts automatically through this setps:
<br/>
0- Put all the APDL scripts in a folder with ONLY the scripts inside.<br/>
1- Open "Sequential_File_Running.py" with a text reader (e.g. Notepad++).<br/>
2- Under "USER DEFINED PARAMETERS" put as directory (WorDir) the folder where you stored all the APDL scripts and give a name at the project (NameProj).<br/>
3- Open Ansys Workbench.<br/>
4- Go to   FIle -> Scripting -> Run Script File.<br/>
5- Run "Sequential_File_Running.py".<br/>

<br/>
If you are interested in copying all or some files from the solution folders follow these steps:
<br/>
0- Open "Post_Process.py" with a python editor.<br/>
1- Under "USER DEFINED PARAMETERS" put as directory (WorDir) the folder where you stored all the APDL scripts, give the path of the folder where you want to save the copied results (NewWorDir), give a name at the project (NameProj) and write all the extension you need to copy from the result folder (Ext).<br/>
2- Run "Post_Process.py".
