wgetdlscript
============

wget Download Script, to replace bloated download managers

This is a simple, SIMPLE bash script I wrote to replace download managers for queing your favourite downloads overnight.  It utilises wget and bash, and nothing else.

To use, create a text file with the following format:
<br />
`www.example.url/example.pdf example.pdf`
<br />
`www.example.url/test.mp4 test.mp4`
Note there can not be any whitespaces in the url or the filename, as this will cause problems.
Save it as a plain file, and then run the wget script as follows:

`dl /path/to/text/file`

It will download the links to the current directory, with the specified file names that you created next to the url in the text file.  Simple!
