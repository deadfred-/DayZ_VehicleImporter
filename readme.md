## ~DayZ Vehicle Importer~ ##

### [Create custom vehicle spawns] ###

Create custom vehicle spawns for your DayZ Reality server.

### [Simple step by step tutorial] ###

1. 	Start your DayZ and press (ALT + E) to open the 3D mission editor.
1. 	Place the vehicles you want to be spawned
1. 	Place the following (Center > Group >Unit) so you can save the mission
1.	Open the tool and enter your MySQL settings
1. 	Just follow the step by step button. All you have to do is to click the button several times until the tool says you’re done.
1. Restart your server
1.	Enjoy your custom vehicle spawns.


####[Dependencies] ####
~.Net Framework 3.5

### [Screenshots] ###

![](http://db.tt/23jR6sbB)
![](http://db.tt/SeJTMY3c)
![](http://db.tt/rGea02JS)


### [Changelog] ###
	[V1.21]
	- Function to add vehicles to your 'vehicle' table if they don't exist
	- Added restart button so you can start from step1 again without restarting the whole application
	- Added a panel that shows you what vehicles have been removed from the import list because the don't exist in your 'vehicle' table
	- Some other minor changes
    [V1.20]
    - Fixed an error where the tool does not close completely if you exit it from the settings window.
    - Added an option where you can choose to start from an custom vehicle ID. >ONLY USE THIS IF YOU KNOW WHAT YOU'RE DOING<
    - Added some information messages for certain steps
    - Cleaned and commentet the code, mostly for myself
    - Fixed a few spelling errors
	- Vehicles that are not found in your "vehicles" table will now be removed from the list of vehicles to import. This is to prevent errors.
    [V1.10]
    - The tool can now import buildings too. Expect a few little updates to come since this feature is currently experimental. 
    [V1.00]
    - Initial Release and GIT setup
