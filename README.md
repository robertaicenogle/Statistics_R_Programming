# Statistics_R_Programming
An overview of the R Program.

## Overview


### Install R
-  **Install R** before installing RStudio
-  To install R on macOS or Windows, navigate to https://cran.r-project.org/mirrors.html
-  Select a mirror link near your region (US)
-  On the download page, follow the appropriate download link (macOS or Windows)
-  On macOS environment, select the latest release .pkg file (the link is midpage)
-  On Windows environment, click on the base installer link. On the next page, click the "Download R for Windows" link to start downloading the installer
-  Run the downloaded file
-  Use all default install options and, if prompted, check all boxes to allow all R components to install.

### Install R Studio
- Navigate to https://www.rstudio.com/products/rstudio/download/?utm_source=downloadrstudio&utm_medium=Site&utm_campaign=home-hero-cta#download
- Select the most appropriate installer link
- For macOS, drag the RStudio application into your application folder
- For Windows, run it through the installer as you would with any other Windows program

### R Studio Configuration
- Four panes within the application window
- Top-left pane contains your source, or any RScripts, tables, and files you open within RStudio
- Bottom-left pane contains the R console
  - Can interact with the environment in real time and test parts of our code before we write them in our scripts)
- Top-right pane contains our environment objects (such as variables, functions, and data frames)
  - Helps us keep track of the shape, data type, and contents of each variable without having to print out our variables in the console
  - Useful for tracking what each line of code does to our data
- Bottom right is the multi-tool pane
  - Contains tabs for a file explorer, R documentation help, installed package list, and a plot viewing tool
    - Plots tab for exploring our generated plots
    - Use the Files tab to open RScripts from your computer or to copy file paths to include within your RScripts
    - Finally, to learn more about a function or object from a library in R, simply type ?<name of function or object> in the R console to open the documentation
