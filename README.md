# Workvivo-Chatbot
<p>
  Note:<br><br>
  This node server was tested on a secured web proxy environment.<br>
  Chatbot will requires to be communication over secured https communication.<br>
  To do so, either modify app.js to use ssl certificate or place it behind a https capable reverse proxy. 
</p>


<p>
<b>To Do:</b><br><br>
1. Configure your environment. (file: .env)<br>
....<br>
PORT= <i>YOUR WEB SERVER SERVICE PORT</i> <br>
IMAGEURL= <i>YOUR WEB SERVER PATH TO PUBLIC DIRECTORY</i> <br>
WORKVIVOID= <i>YOUR ORGANIZATION WROKVIVO ID</i> <br>
WORKVIVOTOKEN= <i>YOUR WORKVIVO API BEARER TOKEN</i> <br>
....<br><br>
2. Make sure app.js (this) and package.json is present in the same directory.<br><br>
 $ npm install<br>
  <br>
3. Run the script<br>
  <br>
 $ node app.js<br>
   or<br>
 $ pm2 start app.js --name "Workvivo-Chatbot"<br><br>
</p>

<p>
<b>Workvivo Support Documents:</b>

Chat Bots (guide to configure your chatbot infrastructure)<br>
https://support.workvivo.com/hc/en-gb/articles/23790354570013-Chat-Bots-Alpha-Release

Bots (guide includes the API method)<br>
https://developer.workvivo.com/#6bde2e09-95dc-48ac-8686-b5c29dbe347c

API Authentication - Bearer Token (guide requirements to use API)<br>
https://support.workvivo.com/hc/en-gb/articles/24560593493661-API-Authentication-Bearer-Token
</p>
