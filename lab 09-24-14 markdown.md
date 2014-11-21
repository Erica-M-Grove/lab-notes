#Code and Poetry Markdown, files lab 09-24-14
•	Backups for word, blog, email are all different  
o	Through plaintext would have one way to back up, one way to search  
o	Benefits both in productivity and politics from doing this  
	Can encrypt and preserve  
o	Through unifying you can use much more powerful tools which would augment your capacities  
	Pointing out when you use a word too often, highlighting words you dislike (for example)  
o	Useful ways to unify: plaintext, Markdown  
o	The editor doesn’t matter with plaintext/Markdown  
##•	Markdown
o	The formatting is human readable  
o	Formatting  
	Bullet points: - word  
	Emphasis (bold): **word**  
	Emphasis (italic): *word*  
	Heading: #word  
	Subheading: ##word  
	Sub-subheading: ###word  
	Two spaces with carriage return for new line  
	Quote: > word  
	Footnote: word^[1] (this is where you want the footnote in the text); [1]: word (this is the footnote)  
	Link: the [link] (www.google.com)  
	Code block: ` word `  
•	Or if quoting many lines:   
```
Words
Words
Words
````
•	Formatted exactly the way it is (useful when quoting poetry)  
o	Can use markdown on a number of web interfaces (stack exchange, reddit, Wikipedia comments)  
##•	Pandoc: 
o	Universal renderer, but challenging to use because it’s a command line tool
o	Has its own flavor of markdown (intended for academics)  
o	Can use any editor, then will save as markdown file, typeset after writing  
o	Open source tool – can go with any vector you like from here  
o	.bib file: keeps track of your bib, have pandoc find the source in your bib  
o	yaml block: where you put metadata about your document  
  ---
Title:
Bibliography: 
Author:
Category: 

--- 
o	in babun, command to get to pandoc is:  pandoc –so test.pdf test.md  
o	appropriate extension for markdown: md  
o	so: be smart about formatting– guess what type of file I want based on the extension  
o	no such thing as a file name, it is a path to a file  
o	to docx: -so /home/usr/test.docx test.md (that’s long form: shorter is test.docx test.md, takes from directory you’re currently in)  
o	pandoc –h: help
