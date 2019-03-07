# Progress Reports
## 1. Report 1: 7 February 2019
  * Repo created: includes README.md, LICENSE.md (blank), 
project_plan.md, progress_report.md, and .gitignore
  * Project plan outlines the data gathering and analysis necessary to 
complete the project. This may be updated as I continue with the 
project and discover new ways to explore the data.
  * License not yet specified
  * Some data explored:
    * CSV File of Princess movies has no null entries. YAY! There also 
aren't any typos in main character's names, so no editing needs to be 
done to this csv in that regard.
    * Cornell Movie corpus does not contain many animated movies, and 
the movies included are already in the Film Corpus 2.0. If the 
formatting of these movies are easier to code with, they may be used.
    * Film Corpus 2.0 explored briefly. Scripts are neat when printed, 
but look very messy when exploring them, with lots of new line 
characters. Some form of regular 
expressions will most likley be needed to divide the data by character 
dialogue
    * I'm continuing to search for animated movie corpora that are 
publically available to use.

## 1st Progress Report
### What I've accomplished
* I created a csv of dialogue in moana. Dialogue was gathered by 
watching the movie and manually typing lines into an excel 
spreadsheet. I included text, speaker, and if the line was sung 
or spoken. Through my 
[code](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Refining_Disney_Data.ipynb), 
I created a dataframe with all 
columns found in the disney movie csv file, as well as gender, role, and 
start of the scene.
* This csv file was then combined with the larger disney movie script 
corpus to be accessed later for further data clean-up and eventual 
analysis.
* In exploring the disney corpus further, I have found errors in some 
scripts (like in Frozen). In some instances, entries are not in the 
proper column or annotations like script headings are included in 
dialogue.
* Used regular expressions to split the Shrek script found in Film 
Corpus 2.0 into lines of 
[dialogue](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Shrek_Lines.ipynb). 
This will then be split 
further to 
create a dataframe, in which one column is speaker and the other is the 
text.
### What I Plan to do next
* The revealed messiness of some of the disney data was disappointing. 
I'd like to see if I can find any resources online that I can use to 
scrape proper forms of the data into the corpus, instead of manually 
fixing each line. However, considering the accessibility of these 
scripts, in the end manual manipulation might be the only solution
* Refine the method I used to create a list of utterances in shrek to 
make it apply to other dreamworks scripts found in Film Corpus 2.0. Of 
course, this assumes uniform formatting.  
* Turn the Shrek list into a dataframe with two columns: speaker and 
text. The additional columns found in the disney data can then be 
added to this script's dataframe.
### Sharing Plan
Due to copyright laws, I cannot share my data. My data consists of full 
scripts that I do not own the rights to, and therefore cannot 
redistribute. I will however, make my code available to anyone who may 
which to replicate it for research purposes. So far, my code only 
contains small portions of the script data I am working with, which 
wouldn't violate any copyright rules.

### Data Sample
I've included a sample of my corpus in the form of a csv file. It can be 
found 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/data_sample).
