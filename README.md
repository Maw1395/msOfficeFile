# README for Forensics file Command 

 **This is a branch of the file command for linux at 2016/04/16 22:40:54 https://github.com/file/file**
 
 **This edit was conducted by Grady Denton, Michael Woodham, and Shane Bennett**
 
 This edit is to provide file analysis on msoffice, and zip repositories while keeping consistency with the file command by
 unzipping the repositories within the file command, running the main aspect of the file command on these files recursively, then
 deleting these temporary directories and leaving the original file unscathed but its contents revealed. 
 
 This was conducted using the file command itself in conjunction with the unzipping tool written in c by github.com/kuba--/zip
 
 The files edited or added to the original github repository are zip.c zip.h makefile.am and file.c
 
 The changes to the file.c command are appended with Forensics for better search availability. 
 
# Installation Instructions
<pre>
sudo ./configure
sudo make
</pre>
**DO NOT RUN SUDO MAKE INSTALL**
