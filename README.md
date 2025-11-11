> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/akira5204/Crypto-Faucet-Bot/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py FreeFaucet.io_Bot.py`
> 
>  or
> 
> `python FreeFaucet.io_Bot.py`


# Crypto-Faucet-Bot
This bot will cycle through 13 different crypto faucet sites and activate the faucet every 60mins that it is available.

In order to run the bot do the following:

Open 'creds.txt'<br>
	- The formatting is very important in this document<br>
	- You don't need to change any of the site names<br>
	- Replace the word e-mail with the e-mail you want to use for the site<br>
	- Replace the word password with the password you want to use for the site<br>
	- Do this for all of the sites listed<br>
	- Save and exit<br>

Run 'FreeFaucet.io_Bot.py'<br>
	- You only need to run this once<br>
	- It will register the username and password provided in creds.txt for all 13 sites<br>
	- You will need to click the verification links sent to your e-mail when it completes<br>

Run 'FreeFaucet.io_Register_Bot.py'<br>
	- Make sure you have clicked the verification links for each site in your e-mail<br>
	- Run the bot<br>
	- You can minimize the bot while it runs<br>
	- After the bot cycles through all of the sites, it will close the browser<br>
	- When the timer is up and the faucets can be activated again, the bot will open the browser and start the process over.<br>

q