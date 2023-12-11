just reminding you about the situation i am in professor thank you
---
Name: Yadir Ibarguen
Course: cis106
Semester: fall 23
---

# week report 6

### Wildcards

### * wildcard
the * wildcard matches from 0 to any number of characters
* examples:
  * list all the text files in a directory
    *  `ls *.txt`
  * list all the files that start with the word file
    * `ls file*`
  * copy all the mp4 files
    * `cp Downloads/*.mp4 ~/Videos/Movies/`   

### ? wildcard
the ? wildcard matches precisely one character
* examples:
  * list all hidden files 
    * `ls .??*`
  * list all files that have 2 characters between b and k
    * `ls b??k*` 
  * list all files that have a 3 letter file extension
    * `ls *.???`    

### [] wildcard
the [] wildcard matches a single character in a range can also use the exclamation mark to reverse the match
* examples: 
  * match all files that have a vowel after the letter f
    * `ls f[aeiou]*`
  * match all the files whose name has at least one number
    * `ls * [0-9] *`  
  * match all files that do not have a vowel after the letter f
    * `ls f[!aeiou]*`    

### brace expansion
allows you to generate arbitrary strings to use with commands
* examples: 
  * create a whole directory structure in one command 
    * `mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}`
  * create an N number of files
    * `touch file (A..Z).txt` 
  * remove multiple files in a single directory
    * `rm -r {dir1,dir2,dir3,file.txt,file.py}`   

