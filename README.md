<h1 align="center">OpenSea NFT Sniping Bot</h1>
<p align="center">
  <a href="https://github.com/Zeeshanahmad4/Facebook-Automation-bot-with-Multilogin-and-Proxies">
    <img src="https://github.com/Zeeshanahmad4/My-Path-to-Python/blob/master/multimedia/fullcrop.png" alt="Logo" width="140" height="220">
  </a>
</p>
<div align="center">

  <a href="https://join.skype.com/invite/y8jt9Ecc32SF">
  <img  align="center" alt="Abhishek's Discord" width="30px" src="https://edent.github.io/SuperTinyIcons/images/svg/skype.svg" />
<code> zeeshan.ahmad400</code>
	</a>
  <span> ┃ </span>
<a href="https://mail.google.com/mail/u/?authuser=ahmadzee26@gmail.com">
  <img align="center" alt="Abhishek Naidu | Twitter" width="30px" src="https://edent.github.io/SuperTinyIcons/images/svg/gmail.svg" />
	<code>ahmadzee26@gmail.com</code>
</a>
	<span> ┃ </span>
	
<a href="https://t.me/zeeshanahmad4">
  <img align="center" alt="Abhishek's LinkedIN" width="30px" src="https://edent.github.io/SuperTinyIcons/images/svg/telegram.svg" />
	<code>@zeeshanahmad4</code>
</a>
	<span>┃</span>
  <a href="" style="margin-top: 12px;">
  <img  align="center" alt="Abhishek's Discord" width="30px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/discord.svg" />
	  <code>Zee#0291</code>
</a>
<br />
<br />
</a>
  <a href="https://www.upwork.com/freelancers/~0180a61cf01f9bc71d" style="margin-top: 12px;">
  <img  align="center" alt="Abhishek's Discord" width="40px" src="https://logowik.com/content/uploads/images/upwork.jpg" />
	  <code>zeeshanahmad44</code>
</a>
	
	
<!-- ![](https://visitor-badge.glitch.me/badge?page_id=.Zeeshanahmad4) -->
<!-- ![](https://api.visitorbadge.io/api/VisitorHit?user=Zeeshanahmad4&repo=Facebook-Automation-bot-with-Multilogin-and-Proxies&countColor=%237B1E7A) -->
</div>
	
<div align="center">
  <strong>For Disscussion, Quries and Freelance work. Do reach me 👆👆👆</strong>
</div>
<br />

# Building a series of bots for OpenSea Market Place.
To Dos.
- [x]  Make Bulk Offer Bot
- [ ]  OpenSea Notification Bot - floor,sales,listings - Discord, Twitter,Telegram
- [ ] Art and Metadata Scraping Bot
- [ ]  Bulk Auto deploy and Art Minting Bot
- [ ]  Python Generative Art Bot 
- [ ]  Rarity Ranking Bot
- [ ]  These bots are not open Sources, Suggestions are welcome.
#nft


# Make Bulk Offer Bot

I have three bots for Making low ball Bulk offers Bot#1 using Browser Automation and Bot#2 is using Opensea Apis bot, Bot#3 is using Opensea  Production apis .

### Bot Inputs-

 1. Collection URL 
 2. Metamask
 3. Bid Amount
 4. Bid expiration time  - only for Apis bot
 
The Bot takes collection Url as input and starts making offers on arts of collection. 
I have built two kinds of bots.


## Bot#1  Browser Automation Bot 
- Build on Chrome browser automation  - Python
- The Bot can be a single thread or Multithread depends open Your machine power.
- The Bot is slow because it uses using chrome browser to make offers on arts. The Bot needs to sign every transaction like humans.
- The Bot can not bid using a custom expiration date. It can only choose from 1,7,14,30 days.
- The Bot can break between making offers and requires a powerful machine to make offers on 5k  arts because the chrome browser consumes many resources while running. 

### Pros & Cons of Browser Automation Bot

<div align="center">

|Stats    | 
|---------|
|3-5 offers Per minute       |
|Miss a lot of offers.       |
|Break Some times       |
|Can't Bid on Multiple Collections    |
|Not Customizable We can not add more functionalities into bot|

</div>

Check more on the topic why the browsers consumes so many resources from [here](https://meta.stackoverflow.com/questions/362294/why-do-stale-stack-overflow-tabs-use-so-many-resources)
<br />
You can see the full Demo of the OpenSea Apis Bot from [here](https://www.youtube.com/watch?v=hGNHiymdzyA)

<p align="center">
  <img src="https://github.com/Zeeshanahmad4/OpenSea-Apis-NFT-Bulk-Make-Offer-Bot/blob/main/Browser_automation_bot.gif" alt="animated" />
</p>


## Bot#2  OpenSea Apis Bot 
- Build on Opensea Official Apis.
- The Bot is fast and robust - It does not need to sign transactions.
- The Bot can make offers with custom expiration time from 1 minute to 6months.
- The Bot will never break because its light weighted and uses open sea Offical Apis. 
- The Bot can not make offers on multiple Collections in one run. 
<br />


### Pros & Cons  of OpenSea Apis Bot

<div align="center">

|Stats    | 
|---------|
|5-10 offers Per minute      |
|Does not miss Any offer |
|Does not break but takes time to handle Rejections from Opensea |
|Can Bid on Multiple Collections one after another|
|Customizable We can add more functionalities into bot|

</div>

You can see the full Demo of the OpenSea Apis Bot from [here](https://www.youtube.com/watch?v=hGNHiymdzyA)

<p align="center">
  <img src="https://github.com/Zeeshanahmad4/OpenSea-Apis-NFT-Bulk-Make-Offer-Bot/blob/main/apis_bot.gif" alt="animated" />
</p>

## Bot#3  OpenSea Production Env Apis Bot 
- Build on Opensea Official Apis Deploy and run in Production Env.
- The Bot is fast and robust - It does not need to sign transactions.
- The Bot can make offers with custom expiration time from 1 minute to 6months.
- The Bot will never break because its light weighted and uses open sea Offical Apis. 
- The Bot can make offers on multiple Collections in one run. 
<br/>

### Pros & Cons  of OpenSea Production Env Apis Bot 

<div align="center">

|Stats    | 
|---------|
|30-40 offers Per minute Lighting Fast Speed |
|Does not miss Any offer 100% success rate |
|Does not break also no Rejections from Opensea |
|Can Bid on Multiple Collections in one run alternatively on arts|
|Customizable We can add more functionalities into bot|
|Outbid bot - In Development|
</div>

