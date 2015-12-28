#WarhornPrintSchedules
This simple application will take a CSV file schedule file for an event from the Warhorn site and format the data for printing.

#Basic usage:

* Download the zip file.
* There is an html file called start.html
* open this in a modern browser (Tested in Chrome on Windows 7)
* Select the CSV file from the Warhorn site for the events that you wish to print paper schedules
* Depending on how big your file is and the speed of your computer this may take a minute to run.
* You should now see a series of tables with the Scenario name, levels, GMs, players, etc.
* Each table will print on its own sheet of paper.  Just use the browser's print button.

#Issues
The Javascript CSV parsers do not handle mixed end of line characters very well.  They will produce errors rather than parsing.  If you run into this, use something like gVim to remove the ^M (lf) characters in the file and re-run.