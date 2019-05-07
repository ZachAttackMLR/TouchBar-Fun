# Custom MacBook Touch Bar

![Global Interface](img/global.png)

Customize the touch bar using [BetterTouchTool](https://www.boastr.net).

Includes how I set up my touch bar globally, as well as specifically for Preview, and Typora. Instructions for all but global follow. You can also just download and import my presets from custom.bttpreset.

## Dependencies

[BetterTouchTool](https://www.boastr.net)
[JSON Helper](http://www.mousedown.net/mouseware/JSONHelper.html)
[Typora](https://typora.io)

## General Instructions
1. Download and install BetterTouchTool and JSON Helper. You can use the free trial of BTT, but eventually you will need to purchase a license for it. Costs about $5. 
2. Open BetterTouchTool and follow the configuration prompts.

# Touch Bar Cryptocurrency Price Display

AppleScripts to display cryptocurrency prices on the MacBook Touch Bar using the CoinBase and Kraken APIs. 

Support for: Ethereum, Bitcoin, Litecoin, Ripple, Monero and ZCash. 

![Interface Preview](img/preview.png)

## Instructions to Display Crypto Prices
1. Navigate into BTT preferences
2. Select "Touchbar" on top
3. Select application you want this to display in on the left panel
4. Click the "+ Widget" icon on the bottom. From the "Select Widget" dropdown menu, choose "Run AppleScript and Show Return Value."
5. Click "Advanced Configuration"
6. Rename the script to the name of the coin (or whatever ele you want).
7. Paste the corresponding Applescript in the text box.
8. Drop the cryptocurrency logo (included in respective directories) in the "icon" box.

# Preview

All that's really here is the ability to zoom in and zoom out. Just add new touch bar buttons, and set their assigned actions to the keyboard shortcuts for zooming in (CMD + +) and zooming out (CMD + -).

![Preview Interface](img/prev_pic.png)

# Typora

I take my notes in MarkDown using Typora, which also allows LaTeX. Thus, to aid in note taking in my math classes, I put in some commonly used LaTeX symbols so they're just a keystroke away. This was done exactly like was mentioned in my description for Preview, just more of it. Create a new touchbar button, and then have it paste the text for the LaTeX command you want. I've included a .txt file of all the LaTeX commands.

![Typora Interface](img/typora_pic.png)
