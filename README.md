# 🌊 FLO-2D-AI-Workshop-Data
Data for a workshop that helps users build python scripts for modifying FLO-2D data and output files.

# Load the FLO-2D AI Workshop Data in Google Colab

Follow these steps to load the workshop data and notebook directly from GitHub into your Google Drive.
This method keeps everything in the cloud and avoids downloading any files to your local computer.

1. Open the Notebook in Google Colab

<a href="https://colab.research.google.com/github/FLO-2DSoftware/FLO-2D-AI-Workshop-Data/blob/main/AI_and_Python_FLO_2D_Data_Processing.ipynb" target="_blank">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
</a>


------------------------------------------------

2. Run the Setup Cell to Copy the Data Into Your Google Drive

In the Colab notebook, run this setup code:

# Clone the workshop repository from GitHub
!git clone https://github.com/FLO-2DSoftware/FLO-2D-AI-Workshop-Data.git

# Mount Google Drive
from google.colab import drive
drive.mount('/content/drive')

# Copy the workshop folder into your Drive
!cp -r FLO-2D-AI-Workshop-Data "/content/drive/My Drive/FLO-2D-AI-Workshop-Data"

After this completes, you will have a full, editable copy of the workshop folder located at:

My Drive / FLO-2D-AI-Workshop-Data

This folder contains Data, the workshop notebook, and all required files.

------------------------------------------------

3. Verify that the Data Loaded Correctly

Run this command to confirm the data files are available:

import os
base_path = "/content/drive/My Drive/FLO-2D-AI-Workshop-Data/Data"
os.listdir(base_path)

You should see a list of the workshop data files.

------------------------------------------------

You are now ready to begin working with the notebook and workshop data.


