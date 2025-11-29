# 🌊 FLO-2D AI Workshop Data

This repository contains the data and notebook used for the FLO-2D AI and Python Data Processing Workshop.  
Use the button below to open the workshop notebook directly in Google Colab.

<p>
  <a href="https://colab.research.google.com/github/FLO-2DSoftware/FLO-2D-AI-Workshop-Data/blob/main/AI_and_Python_FLO_2D_Data_Processing.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
  </a>
</p>

---

## 💦 Getting Started in Google Colab

When the notebook opens in Colab, run the following setup cell to copy the workshop data into your own Google Drive.

```python
# Clone the workshop repository from GitHub
!git clone https://github.com/FLO-2DSoftware/FLO-2D-AI-Workshop-Data.git

# Mount Google Drive
from google.colab import drive
drive.mount('/content/drive')

# Copy the workshop folder into your Drive
!cp -r FLO-2D-AI-Workshop-Data "/content/drive/My Drive/FLO-2D-AI-Workshop-Data"
```

Your Google Drive will then contain:

```
My Drive/
    FLO-2D-AI-Workshop-Data/
        Data/
        AI_and_Python_FLO_2D_Data_Processing.ipynb
```

This gives you a full, writable copy of all workshop materials stored safely in your own cloud space.

---

## 📁 Repository Contents

```
Data/                          Example FLO-2D data files for processing
AI_and_Python_FLO_2D_Data_Processing.ipynb     Workshop notebook
README.md                     Instructions and setup
LICENSE                       GPL-3.0 license
```

---

## 💬 Support

If you encounter issues loading the notebook or data in Colab, please contact the FLO-2D Team or create an Issue in this repository.

Happy modeling!
