🥰 Streamfile-Tg-Bot [![License: MIT][License-Badge]](LICENSE)

Don't forget to star ⭐ the repo 🥰

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Streamfile;" />
</h1>

# Streamfile Worker
File To Link Telegram Bot Using Cloudflare Workers.

<br>

## 🗂 Variables
```javascript
const BOT_TOKEN = "BOT_TOKEN"; // Insert your bot token.
const BOT_WEBHOOK = "/endpoint"; // Let it be as it is.
const BOT_SECRET = "BOT_SECRET"; // Insert a powerful secret text.
const BOT_OWNER = 123456789; // Insert your telegram account id.
const BOT_CHANNEL = -100123456722; // Insert telegram channel id.
const SIA_NUMBER = 1234; // Insert a random integer.
```

### Setup:
- Get `BOT_TOKEN` from [Botfather](https://t.me/botfather).
- Change `BOT_WEBHOOK` with your preferred webhook.
- Change `BOT_SECRET` with a powerful secret text.
- Change `SIA_NUMBER` with a random integer (number).
- Get `BOT_OWNER` from [Rose mam](https://t.me/MissRose_bot).
- Get `BOT_CHANNEL` id by forwarding a message from channel to [Rose mam](https://t.me/MissRose_bot).
  - Channel **ID** must start with `-100`.
  - Bot must be **admin** in channel with **edit rights**.

<br>

## ⚙️Deploy
- Create a [Cloudflare](https://www.cloudflare.com/) **account**.
- Navigate to `Workers & Pages > Create > Create Worker`.
- Deploy the worker by clicking **Deploy**.
- Edit the code by clicking **Edit Code**.
- Upload `worker.js` into **Cloudflare**.
- Modify the [variables](#Variables).
- Finally, **Deploy**.

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/SudoR2spr/WD-filestream)
### Setup:
- Once you deployed the bot on Cloudflare.
- Check `XXX.XXXX.workers.dev/getMe` to verify your bot authorization.
- Open `XXX.XXXX.workers.dev/registerWebhook` to register your bot webhook.
- Then you can start using your bot.

<br>

## 📚 Response
```python
Telegram Link: t.me/usernamebot/?start=ZG9uJ3QgZGVjb2Rl
Download Link: XX.XX.workers.dev/?file=ZG9uJ3QgZGVjb2Rl
Stream Link: XX.XX.workers.dev/?file=ZG9uJ3QgZGVjb2Rl&mode=inline
```

### Limitation:
- Telegram Link: `>4.00GB`
- Download Link: `>20.00MB`
- Stream Link: `>20.00MB`

<br>

## 📷 Screenshot
<img src="https://github.com/SudoR2spr/SudoR2spr/raw/main/assets/line-neon.gif" width="100%">

<p align="center">
  <a href="https://raw.githubusercontent.com/SudoR2spr/SudoR2spr/main/assets/WD-filestream.png" target="_blank">
    <img alt="WD-filestream-Tg-Bot" src="https://raw.githubusercontent.com/SudoR2spr/SudoR2spr/main/assets/WD-filestream.png" width="80%">
  </a>
</p>

<img src="https://github.com/SudoR2spr/SudoR2spr/raw/main/assets/line-neon.gif" width="100%">


## Connect with me <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="30px">
<p align="center">
<a href="https://t.me/Opleech_WD"><img src="https://img.shields.io/badge/-𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭 𝐌𝐢𝐫𝐫𝐨𝐫 𝐙𝐨𝐧𝐞™%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
<a href="https://t.me/WD_Topic_Group"><img src="https://img.shields.io/badge/-Wᴅ Tᴏᴘɪᴄ Gʀᴏᴜᴘ%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
<a href="https://t.me/WD_Request_Bot"><img src="https://img.shields.io/badge/-𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭,𝐬 𝐁𝐨𝐭%20%20-0077B5?style=flat&logo=Telegram&logoColor=white"/></a>
 <br>
<a href="https://t.me/Opleech"><img title="Telegram" src="https://img.shields.io/static/v1?label=WD.Zone&message=TG&color=blue-green"></a> 
 <br>
<img src="https://media.giphy.com/media/jpVnC65DmYeyRL4LHS/giphy.gif" width="20%"> 
</p>
 
-----
Credits: [𝐖𝐎𝐎𝐃𝐜𝐫𝐚𝐟𝐭](https://t.me/Farooq_is_KING)

- [![Contact Me On Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Farooq_is_king)

Last Edited on: 26/09/2024

