This is the readme for the QSAY website - it's not that interesting except for people who need to edit the website.  

If you are here to read about quantitative sports analysis you should go to qsayork.github.io 

For website editors:

To edit an entry, navigate through the github to the page you want, then edit the file which is usually named index.qmd.  You can edit using the pen icon, usually in the top right.
Once your edit is complete, click 'commit changes' and this should then rebuild the website, which takes a little while.  You can add an explanation to commit changes if you wish.

To make a new entry, you can download the files in the placeholder post, then rename and edit the files offline.  When uploading a new post, you should add a new directory.  This can be done by adding a new file.  When adding the file, include the new directory name in the filename.  Make sure **not** to include an underscore at the start of the directory or file names, as these are skipped by quarto.  You should however make a new empty file to create the new directory, for example "_tmp".  Once the directory is created, you can then add the new post files.  For a blog post you may need to add datafiles & references.bib files too.  

**Important** 
Do not use the **tidyverse** when making blog posts, as one of the packages, **ragg**, has dependencies which cannot be loaded by github.  

If you have any issues, just contact me - Rich.
