++++++++++++++++++++++++++++++ Hello User! ++++++++++++++++++++++++++++++

Thanks for choosing Effect size calculator! It is a python module, which can calculate Cohen's d value between group means. A link for windows standalone version of the same program is also provided below. Hope you will find it worthy to use.

For any communications, you can mail at sudiptatung@gmail.com

****** IMPORTANT FEATURES !!!!!************

1. It can calculate pair-wise effect size for ANY number of group means directly from excel file.
2. It can handle multiple excel files.
3. The error term obtained from this program is particularly roboust to small sample sizes (references below).

#######   How to INSTALL the program   #################

Download the files or clone them from github https://github.com/sudiptatung/EffectSizeCalculator.git
Using command prompt go inside the folder EffectSizeCalculator. Remain connected to internet (for automatically downloading the dependency modules) and run the following command.

$ pip install -e .

#######   WINDOWS STANDALONE   #############

A portable windows standalone version of the same program is available here https://drive.google.com/open?id=0By26CkLH32wuWTQwOUlvZkZZeUk

You need to download the .7z file, extract it using password: Tung
Then install the .exe file.
Follow the Readme.txt file for assistance.

#######   Before you run the program   #############

You will find a 'sample data.xlsx' file. Save your data in a .xlsx file as given in 'sample data.xlsx'. This data file (.xlsx file) can be saved anywhere in your computer. You need to mention the path of the data file once asked for input file path.

#######   How to run the program   #################

$$$ from effectsizecalc import cohensd

$$$ cohensd()

Once ran, it will ask for the input file path. Write that correctly within inverted commas. If you have data in multiple excel files, give the path of the first file and wait till it asks for further file path. Once all the calculations are done, the program will ask whether the user wants to save the results in an output file or not. Respond appropriately and give a file path for the output file and it will ba saved.

******** REFERENCES ********************************

1. This program calculates effect size (Cohen's d) following Table 1 and Table 3 of
Nakagawa, S. & Cuthill, I.C. (2007) Effect size, confidence interval and statistical significance: a practical guide for biologists. Biological Reviews, 82,591–605

2. The primary reference for calculating the error term is located at Page 284 of

Hunter, J. E. & Schmidt, F. L. (2004). Methods of Meta-Analysis: Correcting Error and Bias in Research Finding, 2nd edition. Sage, Thousand Oaks, CA.

This error term is particularly roboust to small sample sizes. Cite these references wherever necessary.

****************************************************