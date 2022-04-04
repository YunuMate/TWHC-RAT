# TWHC-RAT
A RAT made for The Whore Hacking Community

# What is TWHC-RAT?
The WWHC-RAT is a Remote Access Trojan fully written in Python 3 and is made for The Whore Hacking Community. TWHC-RAT is based of Sp00p64's DiscordRAT V2

# Disclaimer:
The author will not be held responsible for any misuse of this tool.

# Setup Guide:
You will first need to register a bot with the Discord developper portal and then add the bot to the server that you want (make sure bot has administrator privileges). Once the bot is created copy the token of your bot and paste it at line 17.

Install requirements:
```
pip3 install -r requirements.txt
```
Then if steps above were succesful after launching the python file by doing `python TWHC.py` , or launching the executable , it will create a new channel and post a message on the server with a generated session number.
Now your bot should be available to use !

Requirements:
Python3,Windows(x64)

# Compiling to .exe (Optional)
If you want to compile the bot to exe you can use PyInstaller.
Inside the directory of the bot execute
```
PyInstaller --onefile --noconsole TWHC.py
```
Or
```
python3 -m PyInstaller --onefile --noconsole "TWHC.py"
```
If an error occured during compiling, and it looks something likes this "AttributeError: module 'enum' has no attribute 'IntFlag", whilst compiling to PyInstaller. Please do: 
```
pip uninstall enum34
```
