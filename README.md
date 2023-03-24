# 🦦 0tr.me URL shortener

Hello world! [0tr.me](https://0tr.me) is a free, open source and lightweight URL shortener. It has support for custom domains and decoding short links to expose the long URL behind it. 

## How to self-host it
While I don't plan on providing support for self-hosting, I can tell you some basic things to get you started. This project is programmed in Node (obviously), with Express.js to serve content and qjson-db to store slugs. 

Just clone this GitHub repo, and download all the prerequisites. You can find them in `package.json`.  

You can spin up a free host on Replit or Glitch.com.

---
![hi](https://img.shields.io/badge/.ENV-ECD53F.svg?style=for-the-badge&logo=dotenv&logoColor=black)

The .env file has one simple key in it, used purely to save space in the project. It contains the SVG information needed for the gradient wave in `views/index.ejs`. 

I'm not going to include that in this project, but you can simply grab the code by viewing the source at [https://0tr.me](https://0tr.me). 

## Reporting bugs
It would be great if you could not only report bugs you find (by opening an issue), but create a pull request that helps solve it too. If you contribute, you'll be listed on the homepage forever. 

## License
This project essentially has a do whatever you want license. You can copy code, host this locally, or steal it with or without credit (even though it is greatly appreciated to linkback to my [website](https://willm.xyz)). Please note any `cdn.glitch.global` files are subject to copyright by their lawful owner. 

[![Buy me a coffee]([/assets/images/codey.jpg](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00.svg?style=for-the-badge&logo=Buy-Me-A-Coffee&logoColor=black) 'Buy me a coffee')](https://bmc.xyz/willymuffin)