# UofTHack-V Action on Google: Ships War

Setup Instructions:
Steps:
Use the Actions on Google Console to add a new project with a name of your choosing.
Under Build a custom app, click BUILD in the Dialogflow box and then click Create Actions on Dialogflow.
Click "Save" to save the project.
Click on the gear icon to see the project settings.
Select "Export and Import".
Select "Restore from zip". Follow the directions to restore from the SillyNameMaker.zip in this repo.
In the make_name intent, check “End Conversation” for Actions on Google, then Save.
In Dialogflow, open the Integrations page, open the Settings menu for Actions on Google, then click Test.
Click View to open the Actions on Google simulator.
Type "Talk to my test app" in the simulator, or say "OK Google, talk to my test app" to any Actions on Google enabled device signed into your developer account.

For more detailed information on deployment, see the documentation.

A game which is very similar to BattleShip, making use Dialogflow and Google Assistant...... (to be continued)




###### Special thanks to: #########
        Carleen And Anna, 


-> Improvements <-
- Generate error messages:
1. if user tries to place a ship on a location which already has a ship 
2. if user is giving invalid coordinates (out of bounds)

- Add 2 game modes : Easy and hard

- Allows the user to change the ship locations after placement

- Implement various dimensions of the game, for example: 5 x 5, 6 x 6 ,  10 x 10 and allows users to add more than 3 ships to the game

- Randomize the location of ships for enemy board

- Allows the user to have a display of the game while placing the ships or when trying to guess the locations of the ships

-Debugggg!!
