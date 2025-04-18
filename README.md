# Ex01_Installation_of_DA
AIM:
To install and configure data analysis and visualization tools such as Python (with Jupyter Notebook, Pandas, Matplotlib), R (with RStudio, ggplot2, dplyr), Tableau Public, and Power BI, to prepare for performing Exploratory Data Analysis (EDA).
EQUIPMENT REQUIRED:
Laptop/PC with internet access
Operating System: Windows 10 or above / Ubuntu / macOS
Admin privileges to install software
Web browser (Chrome/Firefox/Edge)

THEORY:
Exploratory Data Analysis requires efficient tools to clean, manipulate, and visualize data.
Python: Versatile programming language, with libraries like Pandas and Matplotlib for data handling and plotting.
R: Statistical programming language, widely used in academia and research with visualization tools like ggplot2.
Tableau Public: Interactive visualization tool with dashboard support.
Power BI: Business intelligence tool for data visualization and report generation.

ALGORITHM:
A. Installing Python (Anaconda Distribution)
Go to https://www.anaconda.com/products/distribution.
Download the installer based on your operating system.
Run the installer with default settings (recommended).
Open Anaconda Navigator → Launch Jupyter Notebook.
Create a new notebook and run the code.

PROGRAM:
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
print("Python tools are working fine.")

#PYTHON INSTALLATION TEST
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

print("Pandas version:", pd.__version__)
print("Numpy version:", np.__version__)
print("Matplotlib version:", plt.__version__)
print("Hello, Python is successfully installed!")




B. Installing R and RStudio
Download and install R from https://cran.r-project.org.
Download and install RStudio (an IDE for R) from https://posit.co/download/rstudio-desktop/.
Launch RStudio.
Install core libraries:

PROGRAM:
install.packages("ggplot2")
install.packages("dplyr")
install.packages("tidyverse")
print("R tools installed and loaded successfully.")

      #R INSTALLATION TEST
install.packages("ggplot2")
install.packages("dplyr")
library(ggplot2)
library(dplyr)
print("Hello, R is successfully installed!")

C. Installing Tableau Public
Go to https://public.tableau.com/en-us/s/.
Download Tableau Public and install it.
Create a free Tableau account and sign in.
Open Tableau → Load a sample dataset → Drag and drop fields to create a chart.
D. Installing Microsoft Power BI
Visit https://powerbi.microsoft.com/en-us/desktop/.
Download and install Power BI Desktop.
Launch Power BI and import any sample Excel/CSV data.
Create a basic bar chart or line chart.


EXPECTED OUTPUT:
A.Python Installation
Pandas version: 1.5.3
Numpy version: 1.24.3
Matplotlib version: 3.7.1
Python successfully installed.

B. R Installation
[1] "Hello, R is successfully installed!"
C. Tableau Public / Power BI
Successful launch of the software.
Ability to import datasets (e.g., Excel, CSV).
Display of sample charts or dashboards using drag-and-drop interface.

RESULT:
The following data analysis and visualization tools were successfully installed and verified:
Python (Jupyter Notebook with Pandas, NumPy, Matplotlib)
R (RStudio with ggplot2 and dplyr)
Tableau Public
Microsoft Power BI
