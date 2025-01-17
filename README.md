# Remove Stripes, Scratches, and Curtaining Artifacts from Micrographs

The destripe script is designed to remove structured artifacts commonly found in electron microscopy data.

For a more detailed discussion, please see the publication associated with this package: 
**"Removing Stripes, Scratches, and Curtaining with Nonrecoverable Compressed Sensing", Microscopy and Microanalysis (2019), DOI: 10.1017/S1431927619000254** 


## Getting Started 

The code can be acquired by cloning this repository to your computer, using the green "clone or download" button, or by typing into the command line:
	
   `git clone https://github.com/jtschwar/Removing-Stripe-Artifacts.git`

The parameters can be defined in main.py file through the GUI. Simply run the file and choose an orientation/size for the missing of the missing wedge that will remove the artifacts in Fourier space.   


### Dependencies

The list of dependencies for destripe is stored in the requirements text file. They can all be installed with the following code:

   `pip install -r requirements.txt`

### Dependencies

   `python main_GUI.py -d folder_containing_tif_files -f file_name`
`

## Contribute

We hope you find this package useful in advancing your own research. 
If this code is helpful to you and your work, please consider citing the associated publication: "Removing Stripes, Scratches, and Curtaining with Nonrecoverable Compressed Sensing", Microscopy and Microanalysis (2019), DOI: 10.1017/S1431927619000254 

If you have any comments or concerns, feel free to open an issue.

Issue Tracker:  https://github.com/jtschwar/Removing-Stripe-Artifacts/issues
 
