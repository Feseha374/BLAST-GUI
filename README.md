# BLAST-GUI
A user friendly GUI to NCBI BLAST suite: Developed for BLAST version 2.6.0

********************** HCGS_BLAST GUI Download Page **********************

1. PURPOSE and DISCLAIMER
   The purpose of writing the program was to provide alternative to the standard command line
   usage required by the BLAST application developed at NCBI for LOCAL use by researchers.

   The program offers both database creation and sequence similarity searching by BLAST from
   a single GUI that auto refreshes the database list after each database creation event.

   THE PROGRAM IS PROVIDED AS IS WITHOUT ANY WARRANTY OR LIABILITY. USER DISCRETION ADVISED!

2. PREREQUISITE
   This program is NOT operational without a working installation of BLAST+ (NOT legacy BLAST!).
   BLAST is a US government program that is available for free at the NCBI. If you don't have
   it you need to download and install it before you can be able to use this Local BLAST GUI.
   BLAST+ can be downloaded from the following site:  NCBI BLAST Download Link
   OR copy and paste this link to your prowser:
   		ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/

   Choose the BLAST+ package suitable for your OS
	Mac OS  users: choose the dmg file at the end of the list
        Windows users: choose the win32.exe or win64.exe file

   Install BLAST+ to the default location by acceptibg default settings 
   which will place the BLAST executables in the default directories:
   
      MacOS X: /usr/local/ncbi/blast/bin
      
      Windows: C:\program files\ncbi\blast\bin       or something similar to it ...
      

3. FOLDER CAUTION ...
   On Windows PC the program assumes that C:\ is the root directory or it would not work.
   Deleting or Renaming the following folders may crash	the program so you keep them intact!

      On Windows:  C:\localBlast    and  C:\blastDB
      
      On MacOS X:  $HOME/localBlast and  $HOME/blastDB   ( $HOME = user's home directory )


