This code analyses changes in artisanal small-scale (ASM) mining activity at an illegal mining site in Bisie in the DR Congo (DRC) between the years 2016 and 2022 (Kranz et al. 2017). While ASM provides a livelihood to more than 45m peoples globally, it also is associated with financing military conflict groups and environmental degradation, such as deforestation and mercury pollution (Nayameyke et al.2021). This code calculates the NDVI for Sentinel 2A imagery as well as the change of the NDVI between the years 2016 and 2022. Prior to the NDVI calculation, the code first loads and reads the imagery into memory, inspects several key characteristics of the imagery, and displays the False Colour Composite of the imagery for both years. 

	Setup and installation 

a)	Download my repository at my Github. You can find my repository at the following link: 
The repository includes: 
-	The Jupyter script for the code “Assignment_Script”
-	The data files “sub_16.tif”, “sub_22-tif”)
-	The Environment as environment.yml 
-	Readme
-	License 
-	gitignore

This code is written as a Jupyter notebook. To run this code, you best install Anaconda and the Jupyter notebook. 

b)	Install Anaconda – if you do not have installed it yet. To install follow the instructions provided at the following link: https://docs.anaconda.com/anaconda/install/
c)	Once you have Anaconda installed, you need to set up the appropriate Environment to run this code.  To do this, you have to import the Environment that you downloaded from my repository. To do so, click on import, then navigate under “Local Drive” to the location where you have saved the environment from my repository. This will create an environment with python version 3.9. 

The packages you need to run this code are the following: 
•	Python (version 3.9)
•	Cartopy (any version)
•	Jupyter notebook (any version)
•	Rasterio (any version)
•	NumPy (any version)
•	Matplotlib (any version)

d)	Open Jupyter Notebook, upload and open the script. 


