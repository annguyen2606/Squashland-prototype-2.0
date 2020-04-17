--Squashie Prototype--
1. Server and UI prototype are currently connecting via socket at local IP "192.168.0.3", You may like to change the IP in "res/xml/network_security_configuration.xml" and MainActivity.kt, line 149 to LAN IP of your machine
2. Socket events fire in "background" task of server.py and in MainActivity.kt on client side
3. Static variable include "socket", "currentSong", "queue", "library" on client application are initialised in MainActivity.kt and extracted from socket events fire from server
4. Add animation on logo in activity_main.xml whenever there are a song playing on server to improve the user experience
5. Recycler view items on activity_choose_a_song.xml now are thicker makes users feel like they are clickable
6. Non-case sensitive search on recycler view in activity_choose_a_song.xml implemented
7. Items on recycler view are now set with onClickListener which will pop up a dialog box to ask confirmation from users on recent selection
8. Daydream service serves as screen saver with label "Squashie Screen Saver" will be avaible as screen saver. To swap the screen saver to "Squashie Screen Saver" go to Settings -> Displays -> Advance -> Screen Saver -> tap on current screen saver and select "Squashie Screen Saver". The tablet/emulator will activate the screen saver regardless of whatever app running in background.
