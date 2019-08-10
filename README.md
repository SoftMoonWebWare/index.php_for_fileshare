# index.php_for_fileshare
single file generates an HTML directory/folder index with hyperlinks, filtertering in filetypes of your choise.  Other file types will not be included.

Subdirectories are included.
The generated HTML page allows end-users to expand/collapse sub-directories with 3 options:
1. expand all sub-directories - links to the files in the current directory and the sub-directories and all their files (and recursively their sub-directories) are shown.
2. collapse all sub-directories - only links to the files and sub-directories in the current directory are shown.
3. open sub-directories individually - allows the end-user to open and close them seperately.

The file is a complete basic HTML5 frame.
Note the &lt;base&gt; tag in the &lt;head&gt; with may be modified/removed - see the comments for more info
  
You may modify the filetypes that are listed in the index to suit your needs.  See the middle of the file (between the &lt;head&gt; and &lt;body&gt;) in the PHP section.
  
From there, if you know what you are doing, style it any way you want, add any additional content you want.

To use:
just drop it in the folder on your server that you want indexed.

you can then see the generated index like this in your browser (for example):

&#104;ttp://mywebsite&#46;com/share/

or this (for example):

&#104;ttp://mywebsite&#46;com/share/index.php

Aloha!

p.s. it is really annoying that even when I encode the fake website examples above with HTML entities, they show up on github as valid hyperlinks.  don't click on them.
