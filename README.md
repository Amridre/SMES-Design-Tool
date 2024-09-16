# SMES-Design-Tool
This repository contains a tool developed in Matlab to design SMES systems. 

User manual

1 - This application is aimed at people who want to familiarize themselves with some SMES terms and people, particularly higher education students, who need a coil sizing tool to help them design a superconducting coil (SMES) by optimizing some of its parameters, such as inductance and superconducting tape length. The program can also be used for coils made of non-superconducting materials, but the native database contains data relating only to a superconducting coil with defined parameters, so the results may not correspond to what is desired if it is used for coils made of other materials.    

2 - To use this application, you need MATLAB runtime. If the user has MATLAB installed, all they have to do to use the application is run the executable file; if they don't, the folder provided has an executable file that installs MATLAB runtime. A free disk space of 2.12 GB is required.

3- In the folder downloaded from github there are 2 subfolders: the first contains the executable for those who don't have MATLAB installed and want to install it, (after completing the installation, a shortcut to the program is created); the second contains the program's executable, intended for users who already have MATLAB installed. The latter is the recommended option.

4 - The main functions of the application are to find the coil topologies corresponding to the data entered by the user and to sort the results obtained according to the length of the superconducting tape or the inductance of the coil and to show a sketch of the coil obtained.

5 - The application interface is quite simple, all windows have a button to return to the previous page and a button to exit the program completely, they also have a button to proceed to the next page and when necessary a button to submit the data entered, sometimes the same button serves to submit data and go to the next page. There are also two buttons that act as switches to select one of two options.

In order for the application to work properly, always follow the instructions in the text boxes displayed and respect the units indicated in order to obtain appropriate results. When submitting values, make sure you enter a reasonable tolerance (you can refine your search by decreasing the value). When the program asks you for file names, make sure that all of them have been read correctly and, if any have not, correct them and submit them again, and then move on to the next page. If you don't have data for all the program's topologies, we recommend using the application's native database.

