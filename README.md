# LevelUp-Script-Steam
A Steam NodeJS bot that trades full sets of trading cards for keys.

How to get your shared_secret & identity_secret: 
1: Go to the SDA(Steam Desktop Authenticator) directory. If you have encryption disabled go to step 3. 
2: Open SDA and hit "Manage Encryption". Fill in your encryption key and when asked to create a new one leave the text box blank. This will disable encryption. 
3: Head over to the maFiles folder and open the file named after your accounts SteamID64. 
4: Search the file for shared_secret:"XXXXXXXXXXXXXX=", instead of XXX it should have a code there, it always ends with = 
5: Do the same for identity_secret, it will look similar. 

Commands: !Commands !Level !Check [Keys] !Check !Buy !Buytf !Buypubg !Buygems !Csgobuyany !Tfbuyany !Pubgbuyany !gemsbuyany !gemsbuyone !Csgobuyone !Tfbuyone !Pubgbuyone !Selltf !Sell !Sellgems

Admin Commands: !Admin !Withdraw !Withdrawtf !Withdrawgems !Deposit !TFDeposit !Depositgems !Block !Unblock !Restart !Shutdown
Custom Rates / Config / Game Playing [H]800 SETS [W] 14:1 GEMS etc..

Setup: This is a Node.JS program and you will need Node installed https://nodejs.org/en/ Make sure the Config.Json is filled out correctly including Shared Secret and Identity, How do you get this? it's provded by SDA (Steam Desktop Authenticator) or WinAuth WinAuth: https://winauth.com/ SDA: https://github.com/Jessecar96/SteamDesktopAuthenticator WinAuth, After adding account to WinAuth right click the Account --> Show Steam Guard And Recovery Code --> Allow Copy --> Details are in the window under Device ID: Set the rates in Rates.Json example 14:1 shown in Config.

Once configured run npm.Bat

After you run npm.Bat(run npm.bat only one time).

run Start.Bat

If you need help or just want to advertise your bot, send me a message on the steam:
http://steamcommunity.com/id/mfx654

