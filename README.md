#WarhornPrintSchedules
This simple application will take a JSON schedule for an event from the Warhorn site and format the data for printing using your brower's print feature.

#Basic usage:

* Download the zip file.
* There is an html file called start.html
* open this in a modern browser (Tested in Chrome on Windows 7)
* Select the JSON file from the Warhorn site for the events that you wish to print paper schedules
* Depending on how big your file is and the speed of your computer this may take a minute to run.
* You should now see a series of tables with the Scenario name, levels, GMs, players, etc.
* Each table will print on its own sheet of paper.  Just use the browser's print button.
* *Note* -> The images used are based on the CAMPAIGN name used.  If there is no campaign name, the Scenario name is printed in large font

#Getting the file from Warhorn
* Log into Warhorn and select the sessions that you want to print
* Click the "Manage Sessions" link in the left menu
* Select the JSON button on the right

* Firefox / Chrome
* This will fill your screen with all of the raw data.  
* Select all of the text and save it in a text file
* This is the file to use above

* IE 11 / Edge
* Microsoft presents a "do you really want to download this" dialog at the bottom of your screen.  Choose "Yes"
* The file will be saved with a ".csv" extension, but it should still work fine.
* To be sure that it downloaded fine, open the file in Notepad.  It will look like the following (with lots more data):

``{"slots":[{"name":"Fri 1/8 2016, 1-5pm","starts_at":"2016-01-08T13:00:00-08:00","ends_at":"2016-01-08T17:00:00-08:00",``
* *If you don't see the leading* ``{``*, the file won't work.  Please try re-downloading it in Chrome / FireFox*

#Current Campaign / Image mapping
* "Pathfinder Society" == img/PathfinderSociety.png
* "Pathfinder Society Adventure Card Guild" == img/PathfinderSocietyAdventureCardGuild.png
* "Shadowrun Missions" == img/Shadowrun_5th_Ed_Missions_Logo.jpg
* "D.*D Adventurers League" == img/DNDRoD_ENCbnnr_728x90.jpg
* "nWoD:.*" == img/World_of_Darkness_Logo.png
* If the campaign is filled in, but not listed above, then the campaign name is output in large type / standard font


All images are copyright of their respective owners.  The images used here are the "Community Use" versions as authorized by the companies as of 1/6/2016.

