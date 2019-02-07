# Animated Movie Dialogue Project Plan
## Description:
Robin Lakoff, in "Language and Woman's Place", created a list of 
characteristics of women's speech. How closely does the dialogue of 
female characters in animation reflect the characteristics Lakoff lists? 
Specifically, I'd like to examine the dialogue of Disney Princesses. For 
the sake of my project, I consider the following characters to be Disney 
Princesses: Snow White, Sleeping Beauty, Cinderella, Ariel, Belle, 
Jasmine, Pocahontas, Mulan, Tiana, Rapunzel, Merida, Anna, Elsa, and 
Moana. 

To see if these female characters adhere to Lakoff's definition of 
women's language more so than other characters, their dialogue will be 
compared to that of male characters in their own films, as well as 
that of characters outside of the Disney Princess genre. As of now, 
several Dreamworks scripts and a few Pixar scripts are available to me.

## Big Questions
1. How much do Disney Princesses use "women's speech" in comparison to 
male characters in their movies?
2. How much do Disney Princesses use "women's speech" in comparison to 
other female protagonists?
3. How much has the dialogue of Disney Princesses changed over time?
  
## Hypotheses:
1. The speaking habits of Disney Princesses have become further 
distanced from Lakoff's list of characteristics of "women's speech" over 
the years.
2. The speaking habits of Disney Princesses will generally be closer to 
Lakoff's list of charactersitics of "women's speech" than the speaking 
habits of non-princess protagonists.

## Data
Data will be gathered from the following sources:
* A csv file of the scripts of Disney Princess movies (up to/including 
Frozen)
  * URL : [Click 
here](https://www.academia.edu/11575608/Corpus_of_Scripts_of_Disney_Princess_Films_1937--2013) 
  * Info: columns are
      * the movie's time period
      * the speaker's utterance
      * speaker classified as princess/non-princess
      * what movie the utterance is from
      * the speaker's name
      * what year the movie was made
      * the utterance number
  * Clean-Up Efforts:
      * After a brief look at the data, there are not any null entries. 
A closer inspection will be needed to weed out possible typos.
      * Moana is not included in this data. I will have to add it
      * Removing The Lion King
      * Labeling characters by gender
      * Labeling protagonist vs antagonist
      * Labeling singing vs dialogue: my project focuses on gender 
dynamics in spoken character interactions, so I don't want to focus on 
song lyrics, but perhaps later I'd like to look at them separately.
* Other animated scripts found in Film Corpus 2.0
  * URL: [Click Here](https://nlds.soe.ucsc.edu/fc2)
  * Info:
      * This corpus includes the scripts of 35 animated movies. 2 are 
disney films not in the corpus above, 5 are Pixar films, 9 are Dreamworks, 13 are from other studios. 
  * Clean-Up Efforts:
      * Because these are raw scripts, I will have to organize the data 
into corresponding categories found in the csv file above.
      * I will also need to specify the production company.
* Other data:
  * I continue to look for available corpora of animated movies. I hope 
to find scripts of more non-princess Disney movies. 

## Analysis
Lakoff's list specifies various things to count and test for in 
each character's dialogue. These include:
* Hedges: Which characters tend to use hedges more than others?
* Adjectives: Do female characters tend to use more adjectives? Do they 
use more of what Lakoff calls 'empty adjectives'? In general, are there 
some parts of speech certain categories of characters use more than 
others?
* Tag questions: How often do characters used tag questions in 
comparison to other questions? In comparison to their overall sentence 
count?
* Politeness: How often do characters use forms like 'excuse me', 
'please', 'thank you', etc? (These counts may need to be checked for 
instances of sarcasm.)
* Apology: How often do characters apologize?
* Cursing: Because this is children's animation, no serious curse words 
will show up in the data. A comparison of soft curse words (ie 'shoot', 
'darn', etc) may be possible.
* Correct Grammar: Does the character use slang? How often?
* Frequency: How often does the character speak in relation to others?

Basic Stats:
* word count
* token count
* word frequencies
* sentence count
* number of utterances throughout the movie
* length of sentences
* What vocabulary band is the speaker's dialogue in?

Other Possible Stats:
* Semantic domains of vocabulary: in comparing a character's dialogue to 
lists of words in specific semantic domains, which semantic domain(s) 
does the character's dialogue align with most?
* How do the stats above vary based on the time period in which the 
movie was created?
* This list will be modified as I explore my data further.

Tough Stats to Track:
* Intonation has been associated with "women's speech", but my data is 
purely text, so intonation may not be a viable avenue to explore.  

##
