<h1>Analyzing Text Files</h1>

##The GNU Project
	The GNU Project has a clone of Pico called nano which has been developed
	because Pico's license was not a free software license, since 
	distribution of a modified version of the code was ambiguously 
	forbidden. By default nano attempts to mimic Pico to replicate the 
	environment users are used to. However it can be configured to offer 
	mouse support, auto indentation, regular expression searches and even
	syntax highlighting making it more useful.

##Challenging assignment: Analyze the treatment of gender in Moby Dick* Create a new project direct* w get file of moby dick* Make a file called male – things that has to do with males* Make another file call female* Grep context of all female and male words in two females* Get rid of common English words* Left with non common gender context words – sort them and count them

##Tools Needed
* find . –name “ora*” //find anything that starts with “ora”* . = find stuff here* / = root * * start with anything wild card* touch  = create* only search home directory ~* head – visualize top* tail – visualize bottom* grep “Mobi Dick” pg2701.txt* grep  this string in this file* prints lines matching a pattern (full text search)* Full text search “what” where | wo* Number of what (first instance in the lines), Number of words in those lines, (characters) bytes* wc – word count* | = pipe* history >> history.txt //put all history into a file* sort (in alphabetical order)* q to get out of vim* uniq –c – sorts it according to number and letter* | less = piped into less so form into arbitrary pages (data is just a stream)* deeply seated idea of lines and characters* sed = streamline editor* ‘s/word/word2/’ ….txt (output) //substitute word 1 with word2* -i ‘s…’ = substitute in place or in file* Install fink in order to work sed	* Sed will substitute only the first in the line, but g after everything in the quotation will substitute global.	* Sed can take a file as an attribute and grep