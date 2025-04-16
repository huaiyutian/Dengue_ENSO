# Rising dengue risk with intensified climate modes and teleconnections under greenhouse warming

Replication code and data for "Rising dengue risk with intensified climate modes and teleconnections under greenhouse warming" 

If you have questions or suggestions, contact the corresponding author.

### Organization 

The repository is organized into **Scripts/**, **Figures/**, and **Data/** folders.

- **Data/**: This folder includes intermediate and processed summary data that enable replication of most the figures and numbers cited in the text. Some of the files for the raw observational data are quite large, so they are not provided here.

- **Scripts/**: Code required to reproduce the findings of our work is included in this folder. Scripts are written primarily in Python (3.9.19) and R (4.4.1) used for the empirical regression analysis.

- **Figures/**: Figures are saved here. Original figures will be saved if you run the scripts. Postprocessing in Adobe Illustrator was used occasionally. Also note that these scripts do not produce the tables found in the Supplementary Material. The tables were made in Microsoft word.

### Installation guide

Instructions for Python 3.9.19:
Download the installer from python.org/downloads.
Run the installer and check "Add Python to PATH" during setup.

Instructions for R 4.4.1:
Windows/macOS: Download from cran.r-project.org.
Linux: Use CRAN repository

The total install time is around 3–10 minutes (including PATH configuration).

### Data 

The full data for the dengue estimates are large, on the order of gigabytes, so they are not hosted in this repo. If you'd like any other data that isn't provided here, please don't hesitate to let me know.

### Scripts

Core scripts of this article are embedded in an R Markdown document **MainCode_enso-dengue**

### Instructions to run on data

1. Open the MainCode_enso-dengue.Rmd file
2. Install required packages in the scripts
3. Set the working directory to the file’s location
4. Run the chunk one by one and generate figures

Expected Runtime: ~30 minutes on a standard desktop (dependent on data size and package dependencies).

Troubleshooting Tips:
If figures fail to generate, check path permissions or disable cached chunks.
For outdated package errors, run update.packages(ask = FALSE) before rendering.
