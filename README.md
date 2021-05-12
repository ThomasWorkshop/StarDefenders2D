# Star Defenders 2D
This is a game made by Eric Gurt. To Play it go to https://www.gevanni.com:3000/ this is a expieriment that adds two new guns, the invisible ones  should be ignored since i didnt make them.  The Two new guns are The "Thomas gun" which is like a mini minigun thats very good at close range, the second is the sniper mk2, unlike the regular sniper it shoots out a burst before having to reload, its damage increases greatly if you hit all 3 shots. Have Fun!

# Installation

In command line (linux, CentOS):

apt update

apt install nodejs

apt install npm

*pick directory*

npm init

npm install express --save

npm install jade --save

PS: You'll probably need latest Node.JS version. If something does not work - you can contact me or discuss it at #sd-discussion at PB2's discord server.

PSS: It is all pretty much same for Windows, just download Node.JS from their official website ( https://nodejs.org ), then follow the instructions towards running simple express application. Eventually just put game files instead of that index.js file and run it. For debugging using Chromium browsers you can run it with command line (cmd.exe application):

node --inspect index.js

After you've done that, green cube icon will magically appear at top left of any open devtools window.

# Start server

You'll need to update SSL (https thing) info in index.js or just get rid of SSL support. It will automatically let it run on Windows without SSL on localhost:3000
Then do:

node index.js > stdout.txt 2> stderr.txt &

# Admin commands

These might change so type /selfhost - it will hint you what to do next. Once you've got admin rights you can type /help for full list of commands you can execute.
