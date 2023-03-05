<h1 align="center">[Discord] - Fake Verification Bot (V2.0.0)</h1>
<p align="center">
  <a href="https://github.com/SenT0417/Discord-Fake-Verification-Bot">
    <img src="https://img.shields.io/badge/License-MIT-important">
  </a>
  <a href="https://www.python.org">
    <img src="https://img.shields.io/badge/Python-3.9-informational.svg">
  </a>
  <a href="https://github.com/SenT0417/Discord-Fake-Verification-Bot">
    <img src="https://img.shields.io/badge/covarage-90%25-green">
  </a>
  <a href="https://github.com/SenT0417">
    <img src="https://img.shields.io/github/repo-size/SenT/Fake-Verification-Bot.svg?label=Repo%20size&style=flat-square">
  </a>
  <a href="https://github.com/SenT0417">
    <img src="https://gpvc.arturio.dev/SenT">
  </a>
    <p align="center"> <a href="https://twitter.com/xsZen_" target="blank">
    <img src="https://img.shields.io/twitter/follow/SenT?logo=twitter&style=for-the-badge" alt="SenT"/></a>
  </a>
</p>

<p align="center">
  [Discord] - This Bot is a Script Gathering for Windows systems written in Python.
</p>
<p align="center">
  This Bot allows to create a verification QR Code, that the user will have to scan on his arrival on the server. Once scanned, you will get his information including his Token.
</p>


## Disclaimer

|Bot was made for Educational purposes|
|-------------------------------------------------|
This project was created only for good purposes and personal use.
By using this Bot, you agree that you hold responsibility and accountability of any consequences caused by your actions.

## Features

- Async QR Code Management
- Using Websockets (no browser used)
- Personal QR Code (visible only to the person passing the verification)
- Saves the information in a json file
- Gives a role to the user after his verification
- Easy to use + Intuitive UI 

## How To Setup/Install

#### First of all please set your informations in the config.json file!
```json
{
    "botToken": "TOKEN-HERE", #For more information, read below
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE" #Name of the role you want to give to the user after scanning the QR Code
}
```
#### Set up and invite your Bot.
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications)
- Enable all instances in the "Bot" tab
- Invite your bot using this [invite](https://discord.com/api/oauth2/authorize?client_id=CLIENTID&permissions=8&scope=applications.commands%20bot) (replace CLIENTID by the ID of your Bot)

#### 1st・Installation (Automated installation)
```
Launch the setup.bat file. A new file will be created. You will only have to launch it.
```

#### 2nd・Installation (Manual installation)
```
$ git clone https://github.com/SenT/Fake-Verification-Bot.git
$ python -m pip install -r requirements.txt
$ python main.py
```

## Additional Informations
General Informations:
- If you find any malfunction, contact me on Discord: SenT#0417.


## Example
![verification_example.png](https://cdn.discordapp.com/attachments/992909137442766878/1004455727517143170/unknown.png?size=4096)


## Credits
leaksfc.

## Tags (Ignore)
Fake Wick Bot, QR Code Grabber, Discord QR, QR Code Scam, Selfbot, Discord Selfbot, Discord Grabber, Discord Rat
