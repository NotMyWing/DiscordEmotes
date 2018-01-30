# DiscordEmotes!!!!!!!!!!!!!!
The most awful way of posting your custom emotes without having Discord Nitro!

# How do I install?

## First of all, get your Discord token from Desktop client
1. Open Discord Client and press `Ctrl + Shift + I`
2. Navigate to `Application` tab, open `Local Storage`, `https://discordapp.com` and copy your token.
    * **NEVER SHARE YOUR TOKEN WITH ANYONE ELSE. NEVER, OR YOUR ACCOUNT <u>WILL</u> BE COMPROMISED.**

## Install Node.JS and Sharp prerequisites

* [Node.JS](https://nodejs.org/en/download/)
* [Sharp Prerequsites](http://sharp.dimens.io/en/stable/install/)

## Install the script itself

1. Clone/download this repository and unpack it somewhere.
2. Navigate into unpacked folder and run `npm install --save`
3. Edit `discordemotes-start.bat` or `discordemotes-start.sh` (if you're using Linux-based OS)
     * Replace YOUR_TOKEN_HERE with your Discord token you obtained in previous steps.
4. Run `discordemotes-start.bat` or `discordemotes-start.sh`!

# How to use

1. Create `images` folder in script directory and throw any images of your liking there.
     * File names should be lowercase.
2. Type `[your_emote]` in Discord. It must be in the end of your message, or in separate one.

## Tips and syntx

* File extension is not needed.
  * `[your_emote]`
* Emotes can be put into nested folders. You need to include that folder when using emote.
  * `[your_folder/your_emote]`.
* Emotes can be chained using comma separator. Spaces are trimmed.
  * `[your_emote, another_emote, third_emote]`!
* Empty emotes can be added by whitespace between commas, acting as empty emote.
  * `[emote,,emote,,emote]`.
* Emotes can be flopped (rotated around X-axis) using `!` prefix before emote. 
  * `[!emote]`.
* Try running script with `--help` key to see additional command line arguments.

## Supported extensions
Next extensions are supported by Sharp
- .jpeg
- .jpg
- .png
- .webp
- .tiff
- .gif
- .svg

Please note that some file formats may not support transparency.

# How do I contact you?
* Discord: Neeve#9079.
* Twitter: [@NotMyWing](https://twitter.com/NotMyWing)
* Use issue tracker on this project.
   
 ## LICENSED UNDER MIT LICENSE
