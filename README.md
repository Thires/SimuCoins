![image](https://user-images.githubusercontent.com/28072996/230968213-94371d57-4573-4d6f-b7f5-7171d18985a4.png)

# SimuCoin
Plugin for Genie frontend to log into simucoin to get current amount, time left or to claim

Commands:<br>
/sc or /simucoin will open the GUI.<br>
/sc username password or /simucoin username password will automatically login using the GUI.<br>
/sct username password will login without the GUI, echoing to game window.
/sca or /scall logs into all accounts saved within the saved xml, echos to game window

Can save multiple usernames/passwords, they will be stored in SimuCoins.xml.
The passwords are encrypted with a randomly generated key each time it is saved.

When window is open, can hit esc key to close it or use window close button.

The clear button will clear the fields currently on the GUI, remove button will remove the currently selected account from the xml.

If simucoins are available to be claimed, they will be claimed when you login with the plugin.

This can be set so that when you login the GUI will pop open for you to claim #trigger {^Welcome to DragonRealms} {#put /sca} or #put /scall
