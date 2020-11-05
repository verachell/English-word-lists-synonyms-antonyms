# English-word-lists-synonyms-antonyms
A list of English words, their synonyms and antonyms. The result of parsing a public domain dictionary of synonyms and antonyms.

## Overview
The words in this list were taken from the Project Gutenberg book: [A Complete Dictionary of Synonyms and Antonyms](http://www.gutenberg.org/ebooks/51155) by Samuel Fallows, 1898

I originally parsed these words for use in my NaNoGenMo 2020 project and put the result of this parsing into this repository in case it was helpful for others to use. 

This repository is licensed under the Unlicense.

USE AT OWN RISK! I have made a good-faith attempt at removing profanity, racial slurs, and other offensive language (see credits for sources of such words), while making a point of avoiding the Scunthorpe Problem. However, there is no guarantee that all offensive language is filtered out, and where you draw the line is largely up to you and your application. The words here should not be considered as free of offensive language; you are responsible for applying your own filters to this. 
## Usage
There are 2 text files with different extensions: `syn-ant.txt` and `syn-ant.csv` The files are in fact identical; I have merely labelled them with separate extensions to make it easier for your computer's default method of opening the file.

### You can probably just stop reading here and just open the files and figure it out from there. If you want to read the full details, limitations, credits etc, read on.

The fields in the file are as follows:

`keyword,synonyms#separated#by#hashes,antonyms#separated#by#hashes`

Note that the antonyms are an optional field. All keywords here ought to have one or more synonyms, but may not necessarily have any antonyms.(What is the opposite of "hamster", for example?)

Your application for reading this data should therefore **delimit by commas for the fields**, and **by hash symbols # for individual synonyms and antonyms.**

Delimiting by spaces will not be helpful, as the only spaces present ought to be in multi-word phrases (e.g. "per annum"). Indeed, most lines are entirely devoid of spaces.

## Limitations
Some words are spelled the same but have multiple meanings. Where a keyword appears more than once in this list, it is because it is also present as its other meaning(s). No attempt has been made here to distinguish between the different meanings. I put this repository together quickly for NaNoGenMo and did not have time to distinguish between multiple meanings of a word. The original book of Samuel Fallows does indicate that distinction, however.

You can safely assume all words are lowercase. I converted these to lowercase during the process. However, this has the drawback that any proper nouns will also be lowercase.

As mentioned earlier, there is no guarantee that all offensive language has been removed.

This was a quickly-put-together list that I did during NaNoGenMo. I will update it if I find problems as I use it. Please also feel free to let me know if you discover any problems.

## Credits
The original words, synonyms and antonyms were sourced from: [A Complete Dictionary of Synonyms and Antonyms](http://www.gutenberg.org/ebooks/51155) by Samuel Fallows, 1898

Words used for filtering out offensive language were sourced from the following:
1. [Banned Word List](http://www.bannedwordlist.com/)
2. [List of Ethnic Slurs](https://en.wikipedia.org/wiki/List_of_ethnic_slurs)
3. [List of Common Nouns Derived From Ethnic Group Names](https://en.wikipedia.org/wiki/List_of_common_nouns_derived_from_ethnic_group_names)
4. [List of LGBT-related slurs](https://en.wikipedia.org/wiki/List_of_LGBT-related_slurs)
5. I also filtered based on some words I thought of, many of which were not offensive per se but could be read the wrong way if put in a certain context. 
