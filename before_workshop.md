# Stylometry workshop installations
## What to install:
### 1. R language
Go to https://cran.r-project.org/ and select version appropriate for your system:
* for Windows: https://cran.r-project.org/bin/windows/base/
* for MacOS: https://cran.r-project.org/bin/macosx/ (R-3.5.1.pkg)
Note that if you use MacOS you need to also install XQuartz (https://www.xquartz.org/) and restart your computer afterwards.  
If you installed XQuartz but still can't install package in the next step, look here: https://github.com/computationalstylistics/stylo#1-installing-from-cran or write me an e-mail with an error you're getting.

### 2. Stylo package
Launch R, make sure you are connected to the internet, and type:
```
install.packages("stylo")
```
choose any CRAN mirror (a window will pop up), and click OK.
  
To check if 'stylo' was installed, type:
```
library(stylo)
```
You should now be greeted with a message:
```
### stylo version: 0.6.8 ###

If you plan to cite this software (please do!), use the following reference:
    Eder, M., Rybicki, J. and Kestemont, M. (2016). Stylometry with R:
    a package for computational text analysis. R Journal 8(1): 107-121.
    <https://journal.r-project.org/archive/2016/RJ-2016-007/index.html>

To get full BibTeX entry, type: citation("stylo")
```
If nothing happened - 'stylo' was not installed, look what the message that appeared after last command says - can you see an error and fix it? If you can't fix it - drop me an e-mail and I'll help you out.
  
You can also try to install 'stylo' another way, e.g. from Github or from a local file. To do so look at general instruction: https://github.com/computationalstylistics/stylo

### 3. Gephi
You should already have it installed if you followed the installation of software needed for Meliha Handzic's workshop.   
Otherwise, go to https://gephi.org/ and download Gephi.  
After installing it, run and check that the program opens.

### Text corpora to download
For a gentle introduction we will use [A small collection of British fiction](https://github.com/computationalstylistics/A_Small_Collection_of_British_Fiction). Please clone or download the folder.
  
We will also use ELTeC corpora for experimental part of the workshop, you can download any (or all):  
[ELTeC corpora adjusted for stylo workshop](https://github.com/JoannaBy/Stylo-in-Galway/tree/master/ELTeC-corpora)

## Help
If you have problems with any of the installation steps, please contact me before the workshop via email to joanna.byszuk@ijp.pan.pl, or at latest - come to the installation session (Wednesday, 8.30am).  
There will be no time for fixing software during the actual workshop.

## Program
**Friday, 7 December 2018: “Stylometry with R”**

09:00-10:30 *Getting started with stylometry*  
10:30-11:00 Coffee break  
11:00-12:30 *Stylometry for literary explorations*  
12:30-13:30 Lunch break  
13:30-15:00 *Authorship attribution*  
15:00 Closing (for both Training School workshops)
