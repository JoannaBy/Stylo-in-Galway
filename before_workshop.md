# Stylometry workshop installations
## What to install:
### 1. R language
Go to https://cran.r-project.org/ and select version appropriate for your system:
* for Windows: https://cran.r-project.org/bin/windows/base/
* for MacOS: https://cran.r-project.org/bin/macosx/ (R-3.5.1.pkg)
Note that if you use MacOS you need to also install XQuartz (https://www.xquartz.org/) and restart your computer after.
If after installing XQuartz you still can't install packages, look here: https://github.com/computationalstylistics/stylo#1-installing-from-cran or write me an e-mail with an error you're getting.

### 2. Stylo package
Launch R, make sure you are connected to the internet, and type:
'''
install.packages("stylo")
'''
choose any CRAN mirror (a window will pop up), and click OK.
  
To check if 'stylo' was installed, type:
'''
library(stylo)
'''
You should now be greeted with a message:
'''
### stylo version: 0.6.8 ###

If you plan to cite this software (please do!), use the following reference:
    Eder, M., Rybicki, J. and Kestemont, M. (2016). Stylometry with R:
    a package for computational text analysis. R Journal 8(1): 107-121.
    <https://journal.r-project.org/archive/2016/RJ-2016-007/index.html>

To get full BibTeX entry, type: citation("stylo")
'''
If nothing happened - 'stylo' was not installed, look what the message that appeared after last command says - can you see an error.
  
You can also try to install 'stylo' another way, e.g. from Github or from local files. To do so look at general instruction: https://github.com/computationalstylistics/stylo

### 3. Gephi
You should already have it installed if you followed the installation of software needed for Meliha Hadzic's workshop.   
Otherwise, go to https://gephi.org/ and download Gephi.  
After installing it, run and check that the program opens.

If you have problems with any of the installation steps, please contact me before the workshop via email to joanna.byszuk@ijp.pan.pl, or at latest - come to the installation session (Wednesday, 8.30am). There will be no time for fixing software during the actual workshop
