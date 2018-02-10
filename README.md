StickerImageBot
===============

Bot to export telegram stickers to images. [Here is a sample one to play with (Not sure it's running)](https://telegram.me/OneImage_Bot)

**Due to the limitation and lack of Telegram API/Documentation, You MUST send all stickers you want to export.**

### Requirements

* Node.js v4.0.0^
* ImageMagick with webp support (Check with `identify -list format | grep -i 'webp'` on *nix systems) (https://www.imagemagick.org/script/install-source.php)

### Usage
0. `yum -y install libwebp-devel libwebp-tools ImageMagick`  and  `apt-get -y install libwebp-devel libwebp-tools ImageMagick`
1. git clone
2. Get a bot token from [@BotFather](https://telegram.me/BotFather)
3. Copy `config.js.example` to `config.js` and edit as your needs
4. `npm install && npm start`

### License

MIT
