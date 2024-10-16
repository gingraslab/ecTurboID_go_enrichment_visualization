# **GO Terms Dot Plot Visualizer**

This repository contains code and data for (TBD)


## **Data description**
Data and figures (TBD)

## **Code instructions**
The complete instruction can be found on:
https://github.com/gingraslab/go_terms_dot_plot

## **Running the Tool**
First you need to clone repository:
```shell
git clone https://github.com/gingraslab/ecTurboID_reprodicibility
```
To run the tool, navigate to the main directory in your terminal and execute the following command:
```shell
python3 src/go_terms_dot_plot.py
```
The tool will prompt you to enter:
1. The directory containing the input Excel files.
2. The number of top terms you wish to extract based on 'p-value'.

### **Example:**
```shell
(base) Admin@Desktop% python3 src/go_terms_dot_plot.py
Please enter the directory: data
Please enter the name of the GO file: hnRNPA1_BFDR1%.xlsx
Please enter the number of top rows to keep based on 'adjusted_p_value' (default is 15): 5
Please enter the term size cutoff (default is 500): 2500
Please enter 'True' for filled version or 'False' for unfilled version (default is True): True
```
The generated plots will be saved in the 'results' folder.

## **Input** 
The tool expects g:Profiler output in .xlsx format.
Each condition should be represented in a separate sheet within the Excel file.

## **Output**
The tool generates a dot plot with:

Top GO terms on the y-axis.
Conditions on the x-axis.
Size of dots representing the number of genes.
Darker color representing higher significance.


## **Sample Files and Results**
There are three sample input files in the 'data' directory for your reference.
Sample results are available in the 'results' directory.
