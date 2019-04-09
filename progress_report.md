# Progress Reports
##  Preliminary Report: 7 February 2019
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

## 2nd Progress Report: 3/19/19
### What I've accomplished
* Created dataframes of the Dreamworks films Antz, Shrek, The Croods, 
How To Train Your Dragon 2, and Rise of the Guardians from script text 
files.
	* In [analyzing the white 
space](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Analyzing_White_Space.ipynb) 
in these text files, I was able to streamline the text to dataframe 
process for The Croods, How To Train Your Dragon 2, and Rise of the 
Guardians. The rought attempt to do this can be found 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Rough_Streamline.ipynb), 
and the 
final streamline can be found 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Streamline_RotG_HTTYD2_Croods_DataFrames.ipynb).
* Annotated the following Disney films with gender, role, and song 
labels: Snow White, Cinderella, Sleeping Beauty, The Little Mermaid, 
Aladdin, Beauty and the Beast, Pocahontas
	* The annotation file uses the dataframe of 13 Disney films 
built 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Refining_Disney_Data.ipynb).
	* The annotation code can be found 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_Data_Edits.ipynb).

### What Needs to Be Done: Data Clean-Up
* The movies Mulan, Princess and the Frog, Tangled, Brave, and Frozen 
must still be annotated.
* The scripts for the Dreamworks films Shrek the Third, How To Train 
Your Dragon, Kung Fu Panda, and Megamind need to be converted into 
dataframes. Once this is complete, these can be annotated using the same 
code used for the Disney film adaptations.
* Linguistic stats, like token and type count, need to be added to the 
dataframe. Other stats, like a speaker's TTR or vocabulary level, will 
most likely be constructed outside the general dataframe because the TTR 
of short lines isn't very informative.

### Sharing Scheme
Because my data consists of copyrighted scripts that can potentially be 
recreated, I cannot share my data. I can only you point you to where I 
found my data. Anyone who wants to use the data must get the proper 
permissions from the data creators. 
The sample provided in 
[data_samples](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/data_sample) 
shows a portion of the Disney data I'm using. This is will be the 
general format of the dataframes in my analysis. Each row consists of a 
time period, gender of the speaker, the name of the movie, the role of 
the speaker as a protagonist, antagonist, or helper, whether the line is 
sung, the name of the speaker, the royalty status of the speaker, if the 
line begins a scene, the line's text, the line's utterance number is the 
film, and the year the film was made.

### Licensing
I have decided to use the GNU General Public License v3.0. I want 
people to have the opportunity to expand on my work, or adapt my code 
for projects of their own. In terms of 
big data, my project data isn't too big, and processing the data 
properly  is time consumming. As demonstrated in my data exploration 
into [Disney 
films](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Refining_Disney_Data.ipynb) 
and [Dreamworks 
films](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/DreamWorks_code/Streamline_RotG_HTTYD2_Croods_DataFrames.ipynb), 
even after a lot of work, data can still be imperfect. Any and all 
improvements on my work so far are more than welcome, and could heavily 
impact results! 

## 3rd Progress Report: 9 April 2019
Note: I have rearranged my code, so the links in report 2 won't work. But, you can find my Disney Data code 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/code/Disney_code), my Dreamworks data code 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/code/DreamWorks_code), and old code that isn't part of 
my final streamline [here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/code/old_code). My introductory analysis 
files can be found in the general [code folder](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/tree/master/code).

### What I've accomplished:
* I've completed by data annotations. I created a pickle file for all 13 Disney Movies, another file for all 9 Dreamworks movies, and one large pickle file with 
every movie in it. See a sample of my data 
[here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/data_sample/all_movies_200.csv).
* Some of my data (Tangled, Frozen, Megamind), was incomplete, incorrect, or just far to messy to parse through. I scraped these. To see an example of my scraping 
code, go [here](https://github.com/Data-Science-for-Linguists-2019/Animated-Movie-Gendered-Dialogue/blob/master/code/Disney_code/Scraping_Tangled.ipynb)
* I've looked at basic token and type count stats for both Disney and Dreamworks. So far, it looks like on average, female speakers have more lines than male 
speakers, but for Dreamworks this isn't true. Of course, other roles the character plays in the movie could account for this. I will use these token/type stats to 
create token/type lists for each character, and see how these vary across time and production company. Ultimatley, I want to see if these movies female characters 
adhere more closely to features of Lakoff's "Feminine Speech". To do this, I will have to analyze...
	* Vocabulary Complexity (comparing both TTR and k-band levels of a character's bag of words)
	* Commands (What percentage of a character's lines are commanding another character): do female characters really use a more complex vocabulary?
	* Does a character tend to be positive or negative in their speech?
	* Use of exclamations/questions: it's expected that more feminine speech will be more unsure. Ellipsis may also be useful in looking at this.
	* Hedging: do female speakers really use more hedge words (ellipsis could also factor into this one)
	* Adjectives and adverbs: Do females really use more flowery language?
	* Politeness: are women really more polite?
	* Interruption: are female characters interrupted more often than male characters?

For stats like politeness and hedges, word lists can either be created or found, then compared to a character's lines. For adjectives/adverbs, part of speech 
tagging can be used. Question marks, exclamation points, interruptions, and ellipsis can be found with regular expressions. Importantly, I need to see if these 
stats correlate the 
most with gender, or something else. 
For instance, whether a woman is a protagonist, antagonist, or a 
helper could 
seriously affect these stats. Maybe their royal status also comes into play. I personally think that the character's role in the plot will influence these 
statistics more than gender will.


