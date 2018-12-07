# Stylometry for Exploration of Literature
  
## Try out basic methods
Follow [this](https://computationalstylistics.github.io/stylo_nutshell/#preparing-a-corpus) for the presentation -  instructions below allow for quick copy&paste.
### Get your corpus
You already downloaded your A_Small_Collection_of_British_Fiction corpus.  
Find it, rembember where you put it and make sure you have a 'corpus' folder inside.

### Set working directory
* type: '''setwd("the/path/to/my/favourite/folder")'''
OR:
* RStudio users: find your directory in the Files panel, then use **Menu > More > Set as Working Directory**
* R gui users: use **Menu > File > Change directory**

### Conduct your first test(s)
Type: '''stylo()'''
You should now see a window with various tabs and options.
1. Go to OUTPUT and select 'PNG'. Click OK without changing anything else.
2. In FEATURES change MAXIMUM in MFW SETTINGS to 500. In STATISTICS change STATISTICS to Consensus Tree. Go to OUTPUT and select 'PNG'. Click OK.
Compare two pictures.

### Regex for gephi
^[A-Za-z]*

## Free practice
### Datasets
You can choose either of the adjusted* ELTeC corpora:  
[ELTeC corpora for stylometry tasks](https://github.com/JoannaBy/Stylo-in-Galway/tree/master/ELTeC-corpora)  
Look at *[Stylo in a nutshell](https://computationalstylistics.github.io/stylo_nutshell/)* 11-25 slides for help.   
Try to go through the following [exercises](https://github.com/JoannaBy/Stylo-in-Galway/blob/master/exercises.md)  

## More help
Documentation of the package ‘stylo’:
* for (sort of) beginners: a concise [HOWTO](https://sites.google.com/site/computationalstylistics/stylo/stylo_howto.pdf)
* for advanced users: [a paper in R Journal](https://journal.r-project.org/archive/2016/RJ-2016-007/RJ-2016-007.pdf)
* full documentation at [CRAN](https://cran.r-project.org/web/packages/stylo/stylo.pdf)  
If you want to conduct a study on a language different than English, here are some points to consider:
[Stylo and languages](https://computationalstylistics.github.io/blog/stylo_and_languages/)


*adjusted here means renamed, to show the title and author of particular works
