# `massdm`

[![HitCount](http://hits.dwyl.com/alexlyee/massdm.svg)](http://hits.dwyl.com/alexlyee/massdm) 
[![Inline docs](http://inch-ci.org/github/alexlyee/massdm.svg?branch=master)](http://inch-ci.org/github/alexlyee/massdm) 
[![Known Vulnerabilities](https://snyk.io/test/github/alexlyee/massdm/badge.svg?targetFile=package.json)](https://snyk.io/test/github/alexlyee/massdm?targetFile=package.json) 
[![Build Status](https://travis-ci.org/{alexlyee}/{massdm}.png?branch=master)](https://travis-ci.org/{alexlyee}/{massdm})


> MassDM v3, a bot to send DMs to every member of a role in Discord server.
> Can send DMs to @everyone, and to just those who are online.


***Use this tool at your own risk!*** 

You will need one thing installed to make this bot work. If you're on Windows, simply run `install_dep.bat`. It can get the prerequisite program for you, and get the libraries needed for this bot to run!
*To get these libraries after installing node.js on an OS other than windows (if you are installing manually), simply open up a terminal in the bot folder and type "npm install -d" without the quotes.*

- Node.JS(LTS version). https://nodejs.org/en/


**Open `config.json` in your code editor and edit the token with your bot token or your user token.** [or remove the "REM" and replate "YOUR TOKEN" in start.bat]
 - Additionally, you can change the prefix, modify the ID of the user who will control the bot, and the [randomized] delay between each send. If you increase this delay, you will be more safe, decrease it at your own risk.
Once you have that done, save the file.
**Of course, you must properly configure the permissions of the bot. Give it administrative-level permissions in your server.**

  Once you have completed all of the above, you may run `start.bat`.

*If you are not running Windows, you need to open a terminal in the bot folder and type "node app.js" without quotes.*
*If you are running into problems and are unsure whether or not it is a bug, please reference tutorials on how to use Discord bots BEFORE reaching out, because I've been contacted for the same few usage errors countless times.*


Ideas for development:
- [ ] customize bot status
- [ ] further permissions checks
