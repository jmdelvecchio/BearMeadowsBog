Del Vecchio et al, Bear Meadows Bog

You can run the .ipynb file either locally using a conda environment or through Google Colab. 

CONDA:

1. Using a terminal like Anaconda Prompt, build a new environment using the .yml file and activate it with "conda activate". See https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

2. Navigate to the directory in which the files are stored and activate a Jupyter environment (either Lab or classic Notebook) with jupyter notebook or jupyter lab. 

3. Locate the .ipynb script and execute cells


GOOGLE COLAB:
1. Go to https://colab.research.google.com/ and navigate to file -> upload and upload the .ipynb

2. If any packages (eg geopandas) are not on Colab's codebase install them with a call to pip (e.g. pip install geopandas) before attempting to import any packages

3. On the left side of the screen, click on the file folder icon and then the icon with the "upload" symbol to upload associated files. Be sure to adjust any pathnames in thee script to reflect any changes to the pathname from your Google Drive. 

