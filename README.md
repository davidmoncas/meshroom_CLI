# meshroom_CLI #
### Python script to control the phtogrammetry software Meshroom directly from the command line without the use of its GUI ###

Meshroom (#https://alicevision.org/) is an open source tool for creating 3d models out of images, the purpose of this repository is create a code that can use the CLI tool of the software to automate the process of creating 3d meshes.




To run the code it is necesary to have Python 3 installed.
for testing purposes, there is a small database of 6 pictures located in /dataset_monstree-master/mini6 . 


The program can be runned with the run.bat file. You should change the 3 parameters in the bat file to make it work:

-absolute path to the Bin folder inside the Meshroom folder

-absolute path to the folder in which the output files will be stored (if the folder doesn't exist it will create a new one)

-Absolute path to the folder containing the images, the folder should only contain images



*All the paths have to be absolute and written inside quotation marks (""), this is specially important if one of the paths contain spaces.



