# iDFD-BFST
Addressing Agricultural Challenges: An Identification of Best Feature Selection Techniques For Dragon Fruit Disease Recognition

# Table of Content
*	[Getting Started](#getting-started)
    *	[Datasets](#datasets)
    *	[Prerequisites](#prerequisites)
*	[Download and install code](#download-and-install-code)
*	[Authors](#authors)
*	[References](#references)

# Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Datasets
+ The dataset can be found in the **Database** directory.
+ The dataset is collected from [1].

### Prerequisites

We have tested RDTLM on MATLAB 2020a and Python on the Windows 10 operating system. You would need to install the following software before replicating this framework in your local or server machine. 

1. MATLAB 2020a or newer version

    To download the MATLAB software, visit: https://www.mathworks.com/products/matlab.html
   
2. Python version 3.11.6 or newer
   
    To download the Python, visit: https://www.python.org/downloads/ 
    

## Download and install code

- Retrieve the code

```
git clone https://github.com/habib-tamuk/iDFD-BFST.git

```

- To run the program, first install all required software and toolbox. Then do the following instructions:
    - Download the [Database](#datasets) from [1].
    - To preprocess the image run the **Preprocessing.m** program in MATLAB.
    - To prepare the segmented image run the **Segmentation.m** program in MATLAB.
    - Now, run the **Data_Set_Preparation.m** program in MATLAB for dataset preparation.
    - Finally to implement the iDFD-BFST model, run the Python programs inside the **ANOVA** and **LASSO** directory.

## Authors

Rashiduzzaman Shakil, Shawn Islam, Yeasir Arafat Shohan, Anonto Mia, Aditya Rajbongshi, Md Habibur Rahman, Bonna Akter.

For any issue please contact Aditya Rajbongshi, aditya0001@bdu.ac.bd 

## References

1. Reference will be updated soon.
