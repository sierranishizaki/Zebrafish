# Analyze Zebra Box
This script analyzes the output of zebrafish video recording data taken by ZebraBox and displays summary data such as movement over time, average distance moved, average duration moved, and average speed by experimental condition group. 



# Access ZebraBox Example Data
Available for download from dropbox:

```
wget "https://www.dropbox.com/sh/u1g2c6yg8xced52/AACILOQoKlEL0EjtqQwGS1Xda?dl=0"
```


# Usage Information

The script "Analyze_Zebra_Box.Rmd" contains all functions needed to run the example data. Please edit file paths prior to running your own data. 

An example output plot can be found: "ZBox_Example_Data.pdf"



# REQUIRED: 
Prior to running this code on your pwn data, please generate an .xlsx/.xls file with a column labeled "Type" including a label for the injected/experimental condition of each fish this is the 'wells' file found in the 'Load in data' section
