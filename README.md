# DiscordEmotes!!!!!!!!!!!!!!
The most awful way of posting your custom emotes without having Discord Nitro!

## How do I install?

### First of all, get your Discord token from Desktop client
1. Open Discord Client and press `Ctrl + Shift + I`
2. Navigate to `Application` tab, open `Local Storage`, `https://discordapp.com` and copy your token.
    * **NEVER SHARE YOUR TOKEN WITH ANYONE ELSE. NEVER, OR YOUR ACCOUNT <u>WILL</u> BE COMPROMISED.**

### Once you obtained your token, you're ready to go!

1. Install [Node.JS](https://nodejs.org/en/download/)
2. Clone/download this repository and unpack it somewhere.
3. Install [Sharp Prerequsites](http://sharp.dimens.io/en/stable/install/)
4. Navigate into unpacked folder and run `npm install -save`
5. Edit `discordemotes-start.bat` or `discordemotes-start.sh` (if you're using Linux-based OS)
     * Replace YOUR_TOKEN_HERE with your Discord token you obtained in previous steps.
6. Run `discordemotes-start.bat` or `discordemotes-start.sh`!

## How do I actually use this

1. Create `images` folder in script directory and throw any images of your liking there.
     * File names should be lowercase.
2. Type `[your_emote]` in Discord. It must be in the end of your message, or in separate one.
     * Please note that extension is NOT needed.
     * If you place your image in nested directory, you'll have to include that folder in brackets. 
       For example, `[your_folder/your_emote]`.
     * You can even chain emotes. Try `[your_emote, another_emote, third_emote]`!
     * You also can add a whitespace between emotes by typing `[emote,,emote]`.

Supported extensions are:
- .jpeg
- .jpg
- .png
- .webp
- .tiff
- .gif
- .svg

Please note that some file formats may not support transparency.

## How do I contact you?
* Discord: Neeve#9079.
* Twitter: [@NotMyWing](https://twitter.com/NotMyWing)
* Use issue tracker on this project.

## FAQ
* Can I share?
   * Yes!
* Can I edit?
   * Yes. Fork it, and you're ready to go!
* Can I redistribute?
   * As long as you follow MIT license.

## Planned features :sparkles:
* Exporting different parts of outfits.
   * Which'll allow changing them on-fly, as well as sharing.
   
 ## LICENSED UNDER MIT LICENSE.
