## Deploy on any shell including termux
- Fork repo and add your github usernname in [config](https://github.com/X-Electra/X-Asena/blob/master/config.js#L13).
- contact [Dev](wa.me/918113921898) with your forked repo url
- install the following dependencies
    - ffmpeg
    - nodejs
- clone the repo
- change the directory to cloned repo
- run ```npm install```
- run ```npm install qrcode-terminal```
- run ```node .```
- scan the qr
- Done your bot is alive 
- run ```node .`` again to run it again after you stop the bot

---
# ⚠️⚠️ You cant use x-asena without forking

# Using X-asena 
## Creating a plugin 
```javascript
const { command ,isPrivate} = require("../lib/");//importing functions 


command(
  {
    pattern: "ping", //command
    fromMe: isPrivate, /*need to respond for everyone's message
true : only from sudo numbers
false : from everyone
isPrivate same as false but will be considered as true if worktype is private*/
    desc: "To check ping",//description of the command
    type: "user",//command type 
  },
  async (message, match) => {
    /*


PLUGIN CONTENT HERE


*/
  }
);

```
## Sending Messages
### Replying
```javascript
message.reply('Hi')
```

### Media
```javascript
let content = 'https://wallpaperaccess.com/full/5531321.jpg'//can also use buffer
message.sendMessage(content,{}/*options*/,'image'/*change to audio , video while sending audio or video */)
```

### Sticker 

```javascript

message.sendMessage(
      'url or buffer of image or video(max 10 seconds)',
      { packname: config.PACKNAME, author: config.AUTHOR },
      "sticker"
    );

```

### [External Plugins](https://github.com/X-Electra/X-Asena/wiki/Plugins)
## Any Doubts ? 
[![JOIN WHATSAPP GROUP](https://raw.githubusercontent.com/Neeraj-x0/Neeraj-x0/main/photos/suddidina-join-whatsapp.png)](https://chat.whatsapp.com/ESiNt1pudB1Js6QRZtM0jg)
#### Official Image
[![Docker Repository on Quay](https://quay.io/repository/xelectra/xasena/status "Docker Repository on Quay")](https://quay.io/repository/xelectra/xasena)
### THANKS TO 

- [Adhiraj Singh](https://github.com/adiwajshing)
- [Yusuf Usta](https://github.com/yusufusta)
- [Neeraj-x0](https://github.com/Neeraj-x0)
- [Adityan](https://github.com/A-d-i-t-h-y-a-n)
- [SamPandey001](https://github.com/SamPandey001)
- [TSH3PHANG](https://github.com/TSH3PHANG)
- [Diegoson](https://github.com/Diegoson)
- [V1P3R-X](https://github.com/V1P3R-X)
- [Lord-Official](https://github.com/Lord-official)
- [Ajmal-Achu](https://github.com/Ajmal-Achu)


