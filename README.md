# VR_Shooter
This VR Shooter is a game designed by ST21S2-49 group, studying at UC as a part of their ITS Capstone Project.
The designers of this game are:
	- Aditya Iyer
	- Daniel O'Keefe
	- Nihal Singh
	- Raajesh Neupane
The game was designed under the supervision of Ram Subhramanian.

To run the game the following setup is required:
	1) Epic Games (registering/log-in might be required)
	2) Unreal Engine - 4.25.4

To run the game:
	1) Open the project files
	2) Open the "VR_shooter" Unreal Engine Project File
	3) Once Open, load a level from the "Levels" folder
	NOTE: Level 0 is a testing level and will not be able to access once the Level from the Main Menu
	4) Click on "Play" to run the game from the selected level

Looking at Blueprints:
	Player Blueprints:
		1) If you wish to look at the player blueprint, go to the "Blueprint" folder
		2) Open the "Player_blueprint" folder to acces the Blueprint file

		- The Viewport tab shall display the appearence of the player and all the components attached to the player
		- The Event graphs and the functions are a Graphical interpretation of the C++ codes, this is to speed up the programming and make it more visible
		- The functions and the variables used also affect different components

	Target Blueprints:
		1) If you wish to look at the player blueprint, go to the "Blueprint" folder
		2) Open the "Target_blueprint" folder to acces the Blueprint files for the Static and Moving Targets

		- Opening the Blueprints for both targets reveal the internal logic of the targets which can be modified for later uses

Looking at the widgets:
The game uses widgets for the interaction with the user. It provides the information and takes most of the user inputs with the help of widgets.
The widgets available in the game are:

	- Popup (~/Content/Widgets/Popup/"Popup_widget"): The "HIT" popup for every succesful hit
	- Scorecard (~/Content/Widgets/Scorecard/"Score"): The HUD for the game displaying the number of targets left and the avg shootimg time
	- Game Over (~/Content/Widgets/Scorecard/"Game_over") : The Game Over Screen after all targets are destroyed. This screen allows the user to Retry, Quit or got to the Main Menu
	- Main Menu (~/Content/Widgets/MainMenu/"Main_menu") : The Main menu screen offering level switching
