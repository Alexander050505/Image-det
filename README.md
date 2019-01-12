# Dicom image metadata extraction
The objective is to extract Dicom (.dcm) files and display the Dicom tags in a text file.

#Prerequisites
The software which was used to run the python file is the Anaconda 1.9.2 .
Download Anaconda, which is a free and open source distribution from https://www.anaconda.com/download/

We need additional packages to be installed as well in order to extract the Digital Imaging and Communications in Medicine( DICOM ).
The package used is pydicom
To install we run 'conda install -c conda-forge pydicom' on the Anaconda Terminal.

#Post-Installation 
-Open the Anaconda Navigator. Launch Jupyter Notebook. Upload the python notebook.
-The files are generally placed in C:Users/Admin.(If admin is the current user)
 (Incase any other user is running the code place the file in the corresponding folder of that user by copying the file manually.)
-Run the Python notebook file (Dicom_image_metadata_extract.ipynb) by clicking on it.
 or Copy the code from the Dicom_image_metadata_extract.html file into a new Python file.
-Run the source code.
-The Outputs would be stored in two separate output files Output1.txt corresponds to ttfm.dcm and Output2.txt correspond to bmode.dcm.
