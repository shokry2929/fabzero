You need to first install node.js.
Install the http-server npm package. Including '-g' sets the installs the package gloabally, allowing you to use it as a command line tool:
npm install http-server -g
Clone the mods repository:
git clone ssh://git@gitlab.cba.mit.edu:846/pub/mods.git
Use the command line to navigate to the root of the mods repository:
cd mods
Node.js v12.x:

# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs


install http-server

install serialport
install node

install ws

Start up a server:
http-server
Open a browser tab and go to 127.0.0.1:8080 which is the same as http://localhost:8080 to view the server that you just started.
Depending on how to need to use mods you can start local servers located in mods/js, for example, if you start from the root of the mods repository:
cd js
node printserver.js
https://github.com/nodesource/distributions

[Go back to readme file](/readme.md)