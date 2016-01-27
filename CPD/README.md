# Creative Professional Development 

A day exploring the potential of Minecraft for education for Teachers & Parents

<img src="https://cloud.githubusercontent.com/assets/128456/9811986/43a7816e-5872-11e5-86ca-acfaa4c2cbcb.png" width="600">

## Introduction

Minecraft has seen in the past 2 years develop a loosely connected community of educators that have begun to explore the potential of the game as a form of stealthy STEM & STEAM based learning.

Getting involved in that world and trying to contribute to it is very rewarding and gives you a skillset as an educator that's at once useful and transferable.

These skillsets can then be passed on to participants and other learners easily often in a way they are unaware of. For the past 2 years artist Ross Dalziel hasbeen working with [FACT](http://fact.co.uk/) and the AHRC's (Arts and Humanitites Research Network) [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) to explore this area through the [CloudMaker Project](https://github.com/cheapjack/CloudMaker)  

[Whitworth](http://www.whitworth.manchester.ac.uk/) Museum of the Year 2015 have worked with Ross AKA [@cheapjack](http:cheapjack.org.uk) to develop a Minecraft: Pocket Edition Server as a learning resource. It allows people to explore a virtual game space inside the real space of the gallery. 

Today we are going to explore that resource by building and playing on it and look at the educational potential of Pocket Edition and have a brief look at other ways of using Minecraft to learn. 

You can find out more and play on the [WhitCraft server here](http://cheapjack.github.io/whitcraft/)

###Background

CloudMaker and [The Minecraft Of Things](http://minecraftofthings.tumblr.com) sprang from research with [FACT](http://fact.co.uk/), [Dr Mark Wright](https://twitter.com/dr_mark_wright), [Adrian McEwen](http://www.mcqn.com/) and Paul Harter of [PrintCraft](http://www.printcraft.org/) funded by [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) for the [CloudMaker](http://www.fact.co.uk/projects/cloudmaker-making-minecraft-real.aspx) project

Find out more in the [project video here](https://vimeo.com/92258008) 
 
<img src="https://cloud.githubusercontent.com/assets/128456/12619114/981b6de2-c50e-11e5-93db-d76640fdb801.png" width="600">

## The Day

There are so many ways to interact with minecraft but for today we are going to explore [WhitCraft](http://cheapjack.github.io/whitcraft) the Whitworth's Engagement Resource built in pocketmine for mobile devices, iOS and Android.

The image above is the Minecraft: Pocket Edition Player `williamblake` with a custom **Skinseed skin**. William, genius that he is will be helping illustrate our days activity. Many of his(the real William Blake) truly awesome works are in the Whitworth collection. More on skins later.

There are not many people out there using the mobile version in this way so we are pioneers here! The beauty of mobile is you can inhabit the virtual space of the game in the real space and play with similarities and differences. 

Then it becomes a modelling tool for real space that young people are familiar with and I think there is real exciting potential for learning here.


**Morning**

 * **1000** Introduction 
  * Minecraft [FAQ](https://github.com/cheapjack/whitcraft/blob/master/CPD/FAQ.md)
  * Minecraft Pocket Edition 101
   * How to play
   * How to logon to a server 
 * **1100** Move on to the themed activities below: build, explore and test stuff!
  * Explore & Build with the [WhitCraft](http://cheapjack.github.io/whitcraft/) resource and follow the theme activities

 * **1230** LUNCH

**Afternoon**

 * **1300** Play with iMovie to record our own MineCraft experiments based on the morning session
 
  * Improve the forest!
  * Annotate tapestries!
  * Import images (ask @cheapjack for help)
  * Paste wikipedia entrys at relevant coordinates!
  * Make a custom skin for [Engels](https://www.marxists.org/archive/marx/works/cw/volume02/02-376.gif) when he lived in Manchester  
  * Install something in the gallery and work out its volume.

 * **1500** SESSION ENDS


## Explore and Build Themes and Activity

### Nature

<img src="https://cloud.githubusercontent.com/assets/128456/12619222/0e3af2b8-c50f-11e5-848c-01368448666c.png" width="400">

Explore gardens and plantings, compare the real garden with the model

#### Activity

 * Plant saplings in creative mode and use bonemeal to grow
 * Edit the grown saplings to reflect the real park
 * Clear the snow!
 * Switch to Adventure mode and ops can give players individual flowers

`/gamemode 2 <playername>`
`/give <playername> <block.id>`

**Requirements:**
Bonemeal, Flowers, Trees, Google Maps (option), Eyes


### Exploring Collections: Tapestry Teleport

<img src="https://cloud.githubusercontent.com/assets/128456/12558485/bae25e22-c387-11e5-805c-b5c0ab331937.png" width="400">

**Jump inside a giant ["Brer Rabbit" Tapestry](http://gallerysearch.ds.man.ac.uk/Detail/23332) by [William Morris](https://en.wikipedia.org/wiki/William_Morris) from the Whitworth Collection**

#### Activity

 * `/tp -400 100 -400` to the Brer Rabbit tapestry
 * Try build up areas of the tapestry in grass blocks and annotate them with signs
 * Try importing a new image
  * `/tp 1000 100 1000`
  * `/paintimage <playername> http://whitcraft.uk/maps/spacewalk.ppm`

**How to**

You can use the [PaintMyLawn server plugin](https://github.com/shoghicp/PaintMyLawn) to import images to the grassblock floor of a minecraft server. 

To do this you need to install the [PaintMyLawn](https://github.com/shoghicp/PaintMyLawn) plugin and re-start your server or `/reload`.

Use a tool like [ImageMagick](http://www.imagemagick.org/script/convert.php) to convert images to a manageable size (no more than 600x600 pixels) and in the correct format, **.ppm**

[ImageMagick](http://www.imagemagick.org/) is a command line tool for image processing its faster than photoshop or [Gimp](http://www.gimp.org/) and its free (like gimp) and cross platform

#### Example

`$ convert brerrabbit.png -resize %50 brerrabbit.ppm`

The **.ppm** format must have `P6` in the header (ie the first line of the file) of the file (you can view it in a text editor like Mac TextEdit, [Vim](https://github.com/vim) or Windows NotePad. 

**.ppm** is the Portable Pixmap Binary format. See [this](https://en.wikipedia.org/wiki/Netpbm_format) on `.ppm` formats

Then you need to place this image on a webserver somewhere that has `755` file permissions. Then use the command:

<img src="https://cloud.githubusercontent.com/assets/128456/12619359/8c80c51c-c50f-11e5-9612-8b262314e997.png" width="400">

`/paintimage <playername> <full image address http://something.something/myimage.ppm>`

You must be `op` to use this command. It will then if all is well replace the ground floor grass blocks with coloured blocks from the image, centred on the named player.

**Requirements:**
Maps, PaintMyLawn plugin


### Local History

Use signs to illuminate the garden and gallery with local knowledge

<img src="https://cloud.githubusercontent.com/assets/128456/12619376/a4cf93b4-c50f-11e5-8870-945095a1adf6.png" width="400">

**Requirements:**
Signs in game, local knowledge

### Civic Identity

Explore civic/local identity by outlining local buildings

<img src="https://cloud.githubusercontent.com/assets/128456/12619415/ce0c099c-c50f-11e5-8cd6-405b6751f45d.png" width="400">

**Requirements:**
Maps, PaintMyLawn plugin

### Artists at Whitworth: custom skins

<img src="https://cloud.githubusercontent.com/assets/128456/12619457/058330da-c510-11e5-97a6-91d1ef2f2930.png" width="300">

<img src="https://cloud.githubusercontent.com/assets/128456/12619507/41407902-c510-11e5-93f5-97b9f7ddd7b8.png" width="300">

Use apps like Skinseed for [iOS](https://itunes.apple.c m/us/app/skinseed-skin-creator-skins/id675628523?mt=8) or [Android](https://play.google.com/store/apps/details?id=com.africasunrise.skinseed&hl=en) to explore the identity of famous artists connected to the Whitworth collections and exhibitions

**Skins** are the way minecraft represents your player to other players or yourself if you switch into 3rd person view (in options available in-game). Its fairly standard for people to make their own skin over the standard **Steve** character

#### Activity

 * Find some famous or not so famous artists from the [Whitworth Collection](http://gallerysearch.ds.man.ac.uk/) and find an image or portrait and use the Skinseed app to customise an existing skin to represent them 
  * Open Skinseed on the iPad
  * Search for an existing skin then edit to suit artist
  * Export to Camera Roll
  * Go back to Minecraft app, click on `Skins` from main menu
  * Click on `Browse` and find the new skin from your camera roll area of the iPad system
  * Play as a famous artist! 

**Requirements:**

**Skinseed** for [iOS](https://itunes.apple.c m/us/app/skinseed-skin-creator-skins/id675628523?mt=8) or [Android](https://play.google.com/store/apps/details?id=com.africasunrise.skinseed&hl=en) installed on the client device (the iPad/iPhone/Android that you are playing on)

#### Maths and Measurements STEAM/STEM

Our resource does have some links to STEM subjects: Art is a technical business and its only recently that the sciences and arts have been seperated, even a programmer needs the design skills an engineer or artist can learn.

#### Activity

 * Imagine you are an art handler and technician about to install a brand new work in the gallery that currently holds (in the game that is) a model of Cornelia Parker's 'Dark Matter'
 * Use `//pos1` and `//pos2` from the [WorldEditArt Plugin](http://forums.pocketmine.net/plugins/worldeditart.842/) to calculate the volume of the gallery space and use graph paper to plan out a new model
 * Refer to this [guide](https://github.com/PEMapModder/Small-ZC-Plugins/wiki/WorldEditArt-|-Player's-Guide) for WorldEdit in pocketmine.
 
**Requirements:**
[WorldEditArt Plugin](http://forums.pocketmine.net/plugins/worldeditart.842/)


### The End (of the workshop not [the nether](http://minecraft.gamepedia.com/The_Nether))

This should get you started with ideas for using the Whitcraft server and pocketmine to explore learning in Minecraft; Now take what you've learned, experiment and learn how to video and publish your hard work this afternoon!

##Tools & Resources

###Projects

 * [Minecraft Education Edition](http://education.minecraft.net/resources/)
 * [Minecraft projects by Ross Dalziel and FACT](http://cheapjack.github.io/EverythingMinecraft.html)
 * [CloudMaker project](https://github.com/cheapjack/CloudMaker/)
 * [Printcraft](http://www.printcraft.org/)
 * [stuffaboutcode](http://stuffaboutcode.com)
 * [WhitCraft](http://cheapjack.github.io/whitcraft/)
 * [ScriptCraft](http://scriptcraftjs.org/)
 * [Explore space in Minecraft](https://github.com/martinohanlon/exploring-space-with-minecraft)

###Pocketmine

 * [Pocketmine server software](https://www.pocketmine.net/)
 * [PaintMyLawn](https://github.com/shoghicp/PaintMyLawn)

###Further Reading 

 * [Adventures in Minecraft](http://eu.wiley.com/WileyCDA/WileyTitle/productCd-111894691X.html)


