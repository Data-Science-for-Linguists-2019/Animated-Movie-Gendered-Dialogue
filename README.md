# Gendered Dialogue in Animated Movies
## Cassie Maz, 27 April 2019, cmm281@pitt.edu

Cassie's term project. An analysis of how 'feminine' female dialogue is across companies, story role, and time.

A link to my guestbook: [click here](https://github.com/Data-Science-for-Linguists-2019/Class-Plaza/blob/master/guestbooks/guestbook_cassie.md)

## Project Description
Using a handful of features from Lakoff's list of feminine language features, I analyze how well animated female characters adhere to the features. Specifically, I 
look at 12 Disney Princess movies and 9 DreamWorks movies to compare the following:
* How often female protagonists and female antagonists use these features
* How often Disney characters and DreamWorks characters use these features
* How earlier characters (like Snow White) and later characters (like Moana) use these features

## Data Description
My found data are movie scripts, and come from two main sources:
* Disney Princess scripts: [here](https://stanford.academia.edu/LeliaGlass/Corpora)
* DreamWorks scripts: [here](https://nlds.soe.ucsc.edu/fc2)

## Directory

### General Files
* README.md: this file
* [LICENSE.md](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/LICENSE.md): 
the sharing license for this repo
* [Project_Presentation.pdf](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/Project_Presentation.pdf): 
a powerpoint of some earlier findings in my 
project
* [final_report.md](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/final_report.md): 
a summary of all my analysis
* [progress_report.md](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/progress_report.md): 
reports of what I've done for this project in 
Spring 2019
* [project_plan.md](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/project_plan.md): 
my initial goals for this project
* [images](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/images): the various png images I use as visuals for my 
project
* [data_sample](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/data_sample):small examples of the data I'm working 
with

### Code

#### Disney_code
* [Disney_Data_Complete_Edits_Good](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Disney_Data_Complete_Edits_Good.ipynb): 
completed cleanup of the Disney data
* [Final_Disney_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Final_Disney_DataFrame.ipynb): 
A dataframe of all the Disney movies in its final form
* [Messy_Disney_Movies](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Messy_Disney_Movies.ipynb): 
observations on which Disney movies need the most 
clean-up
* [Refining_Disney_Data](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Refining_Disney_Data.ipynb): 
Removing the Lion King and adding Moana
* [Scraping_Frozen](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Scraping_Frozen.ipynb): 
Web scraping a script for Frozen
* [Scraping_Tangled](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Scraping_Tangled.ipynb): 
Web scraping a script for Tangled

#### Dreamworks_code
* [Analyzing_White_Space](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Analyzing_White_Space.ipynb): 
Observations on how white space can be used to sort these scripts by line
* [Dreamworks_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Dreamworks_DataFrame.ipynb): 
constructing and finalizing the DreamWorks 
movies into a dataframe
* [Kung_Fu_Panda_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Kung_Fu_Panda_DataFrame.ipynb): 
converts the .txt script into a dataframe
* [HTTYD_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/HTTYD_DataFrame.ipynb): 
converts the .txt script of How to Train Your Dragon into a dataframe
* [Megamind_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Megamind_DataFrame.ipynb): 
creates a dataframe of lines in the movie Megamind from a web-scraped script
* [Shrek3_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Shrek3_DataFrame.ipynb): 
creates a dataframe from the .txt script
* [Shrek_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Shrek_DataFrame.ipynb): 
creates a dataframe from the .txt script
* [Streamline_RotG_HTTYD2_Croods_DataFrame](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Streamline_RotG_HTTYD2_Croods_DataFrames.ipynb): 
a single piece of code to create dataframes from the .txt Rise of the 
Guardians, How to Train Your Dragon 2, and The Croods scripts
* [antz-Copy1](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/antz-Copy1.ipynb): 
creates a dataframe from the .txt script of Antz
* [httyd_megamind_kungfupanda](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/httyd_megamind_kungfupanda.ipynb): 
an analysis of how to approach these oddly 
formatted scripts

#### Analysis_code
* Preliminary Analysis: A folder of basic analysis and exploration of the 
complete 
[Disney](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Preliminary%20Analysis/Disney_Analysis_Basic.ipynb) 
and 
[Dreamworks](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Preliminary%20Analysis/Dreamworks_Analysis_Basic.ipynb) 
dataframes
* [All_Movies_Analysis_Basic](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/All_Movies_Analysis_Basic.ipynb): 
basic type/token analysis and exploration of the the full dataframe
* [All_Movies_Analysis_Basic_Part_2](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/All_Movies_Analysis_Basic_Part_2.ipynb): 
Similar to the jupyter file above, but with saved image files
* [Char_Token_Type_Lists](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Char_Token_Type_Lists.ipynb): 
creates a new dataframe of every character and their total Token/Type counts
* [Commands_Analysis](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Commands_Analysis.ipynb): 
Finds commands in each line through regular expressions and looks for 
significance in distributions
* [General_Stats_All_Movies](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/General_Stats_All_Movies.ipynb): 
Looks at character distributions by gender and role
* [Hedges](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Hedges.ipynb): 
Finds hedges in each line and looks for significance in distributions
* [POS_Tag_Adj_Analysis](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/POS_Tag_Adj_Analysis.ipynb): 
Tags each line with part of speech and analyzes adjective distributions
* [Politeness_and_Apology](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Politeness_and_Apology.ipynb): 
Finds polite forms and apologies in each line and looks for significance in 
distributions
* [Significance_Tests_Token_Type_TTR](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Significance_Tests_Token_Type_TTR.ipynb): 
Significance tests on token, type, ttr, and k-band distributions
* [Tag_Questions](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Tag_Questions.ipynb): finds tag 
questions with regular expressions and looks for significance in distributions
* [Tok_Type_TTR_Analysis](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Analysis_code/Tok_Type_TTR_Analysis.ipynb): 
Adds TTR and k-bands to the character dataframe and graphs distributions

#### old_code
Code that has been abandoned for one reason or another, but are still 
important to the project
* [command_try_2](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/command_try_2.ipynb): 
the code that eventually led me to my current 
approach to commands
* [interruption](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/interruption.ipynb): 
an attempt to look at interruption as a feature to 
analyze, with poor results
* [Questions_Exclamations_Etc](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/Questions_Exclamations_Etc.ipynb): 
an attempt to look at punctuation, but poor assumptions made
* [Rough_Streamline](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/Rough_Streamline.ipynb): 
the code that eventually became my streamline for parsing 3 Dreamworks 
movies
* [Shrek_Lines](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/Shrek_Lines.ipynb): 
my very first attempt to approach the Dreamworks scripts
* [Topics_by_Gender](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/Topics_by_Gender.ipynb) 
and 
[Topics_by_Gender-Copy1](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/old_code/Topics_by_Gender-Copy1.ipynb): 
both failed attempts to find significant topics of conversation between 
genders

