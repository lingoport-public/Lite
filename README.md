# How to use this demo application For SOFLOC
* Create your own branch from master
* Modify a .java file and commit it: you will get a commit message for i18n correctness based on out of the box (non refined) rules
* Modify a .properties file and commit it: you will have translations for those files in short order.

## Very Simple Application for Demonstration Purposes only
The couple of .java files can show how Globalyzer can be used to detect internationalization (i18n) issues. 
The .properties file(s) can show how Localyzer can be used to machine translate resource files created by developers. 

## Globalyzer Express 
Globalyzer Express is set up on this repository. Any changes to any .java in any branch will trigger a scan of the file. The result of the scan will appear as a commit message associated with that change. The entire file is scanned, independently of the changes. 
Developers can have their files checked for correctness with every commit, making it non obtrusive, yet valueable. 

## Localyzer Express
When one adds, or modify strings in a .properties or create a new file, and commits that change, in whatever branch, the files are translated into a couple of locales using Localyzer Express.

## --

Rebase Test
