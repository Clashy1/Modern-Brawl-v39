# Brawl Stars v39

Experimental Brawl Stars v39.99 server emulator written in Python.

![ScreenShot](https://cdn.discordapp.com/attachments/882329215112970370/904308750666571797/Screenshot_20211031_165222_com.projectbsds.v39server.jpg) 

### Requirements:
- Python 3.7 or higher
- colorama

### Running the server
In a terminal, type __`pip install -r requirements.txt`__ then run the server using __`python main.py`__

### Configuring the client app
To connect to your server, a **patched client** is required. Download this [base APK](https://www.youtube.com/watch?v=dQw4w9WgXcQ) and change the IP in `libhaccing.config.so`. 

⚠️ This client is unstable and might crash sometimes. It is not recommended to use it for a production environment.
### Battles
We've enabled offline battles so you can directly press "PLAY" to start a match.
![ScreenShot](https://cdn.discordapp.com/attachments/704364452891590778/885473792208543774/Screenshot_20210909-133614_BS_v36.jpg) 
Unfortunately, the offline logic is mostly broken and some gamemodes/brawlers might crash the game or not work correctly. 
After multiple tests we've made it appears these 3 gamemodes still behave normally:
- Gem Grab
- Bounty
- Big Game


### Got any question?
Contact @Хлеб | Bread#1567 on Discord or open an issue.

### Important Notice
This is an experimental and incomplete server made just for fun. No database, no data saving. 
The purpose of this project is to prove that making a private server for Brawl Stars is still possible.
We won't provide further updates nor will we offer support for miss-features or other issues.
