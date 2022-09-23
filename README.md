# furry-guacamole

1.Exit to desktop mode if you have not already done so.
2.Install Ubisoft Connect as a non-Steam game using one of the guides around (for example, https://www.gamingonlinux.com/2022/03/ubisoft-connect-on-steam-deck-guide-with-sd-card-access) which includes changing the target to point to UbisoftConnect.exe
3.In your Steam Deck's file manager go to /home/deck/.steam/steam/steamapps/compatdata/ and make a note of the name of the newest numeric directory that has been created. This is your Proton prefix for Ubisoft Connect.
4.Download/Install your game in Ubisoft Connect, and then exit it.
5.Add another non-Steam game, pointed to the same UbisoftConnect.exe in the same directory as above.
6.In launch options, enter uplay://launch/XXX/0 where XXX is the id of your game. You can find what the id should be here: https://github.com/Haoose/UPLAY_GAME_ID
7.You can now customize this new non-steam game entry and rename it to the name of the game you've installed, apply custom artwork for it from steamgriddb.com, and so on.
8.Repeat steps 5-9 for all Ubisoft Connect games you want to add to Steam.
9.124124Note, it's probably a good idea to remove the symlink before removing a Ubisoft game that you want to delete from Steam, then uninstall the game from within Connect.
