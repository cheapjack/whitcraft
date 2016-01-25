# Creative Professional Development 

A day exploring the potential of Minecraft for education for Teachers & Parents

<img src="https://cloud.githubusercontent.com/assets/128456/9811986/43a7816e-5872-11e5-86ca-acfaa4c2cbcb.png" width="600">

## Introduction

Minecraft has in the past 2 years developed a loosely connected community of educators that have begun to explore the potential of the game as a form of social design and learning.

Getting involved in that world and trying to contribute to it is very rewarding and gives you a skill set as an educator that's at once useful and transferable.

These skillsets can then be passed on to participants and other learners easily often in a way they are unaware of. For the past 2 years artist Ross Dalziel hasbeen working with [FACT](http://fact.co.uk/) and the AHRC's (Arts and Humanitites Research Network) [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) to explore this area through the [CloudMaker Project](https://github.com/cheapjack/CloudMaker)  

[Whitworth](http://www.whitworth.manchester.ac.uk/) Museum of the Year 2015 have worked with Ross to develop a Minecraft Pocket Edition Server as a learning resource to allow people to explore a virtual space inside the real space of the gallery. Today we are going to add to that resource and explore the potential of Pocket Edition and other ways of using Minecraft to learn.

You can find out more and play on the [WhitCraft server here](http://cheapjack.github.io/whitcraft/)

###Background

CloudMaker and [The Minecraft Of Things](http://minecraftofthings.tumblr.com) sprang from research with [FACT](http://fact.co.uk/), [Dr Mark Wright](https://twitter.com/dr_mark_wright), [Adrian McEwen](http://www.mcqn.com/) and Paul Harter of [PrintCraft](http://www.printcraft.org/) funded by [IT as a Utility (ITaaU) Network](http://www.itutility.ac.uk) for the [CloudMaker](http://www.fact.co.uk/projects/cloudmaker-making-minecraft-real.aspx) project

Find out more in the [project video here](https://vimeo.com/92258008) 
 

## The Day

**Morning**

 * 1000 Introdcution 
 * 1030 Play explore and test

 * 1230 LUNCH

**Afternoon**

 * Play with iMovie to record our own MineCraft experiments based on the mornign session


## Themes 

### Nature

Explore gardens and plantings, compare the real garden with the model

Switch to survival mode and ops can give players individual plants

**Requirements:**
Bonemeal, Flowers, Trees, Google Maps


### Exploring Collections Tapestry Teleport

<img src="https://cloud.githubusercontent.com/assets/128456/12558485/bae25e22-c387-11e5-805c-b5c0ab331937.png" width="400">

**Jump inside a giant ["Brer Rabbit" Tapestry](http://gallerysearch.ds.man.ac.uk/Detail/23332) by [William Morris](https://en.wikipedia.org/wiki/William_Morris) from the Whitworth Collection**

You can use the [PaintMyLawn plugin](https://github.com/shoghicp/PaintMyLawn) to take pictures of an artwork and then import this image to the floor of a minecraft server. 

To do this you need to install the [PaintMyLawn](https://github.com/shoghicp/PaintMyLawn) plugin and re-start the server.

Use a tool like [ImageMagick](http://www.imagemagick.org/script/convert.php) to convert images to a manageable size (no more than 600x600 pixels)and in the correct format, **.ppm**

#### Example

`user$ convert brerrabbit.png -resize %50 brerrabbit.ppm`

The **.ppm** format must have `P6` in the header (ie the first line of the file) of the file (you can view it in a text editor like [Vim](https://github.com/vim) or NotePad. 

**.ppm** is the Portable Pixmap Binary format. See [this](https://en.wikipedia.org/wiki/Netpbm_format) on `.ppm` formats

Then you need to place this image on a webserver somewhere that has 644 file permissions. Then use the command:

`/paintimage <playername> <full image address http://something.something/myimage.ppm>`

You must be `op` to use this command. It will then if all is well replace the ground floor grass blocks with coloured blocks from the image.

**Requirements:**
Maps, PaintMyLawn plugin


### Local History 

Use signs to illuminate the garden and gallery with local knowledge

**Requirements:**
Signs in game, local knowledge

### Civic Identity

Explore civic/local identity by outlining local buildings

**Requirements:**
Maps, PaintMyLawn plugin

### Artists at Whitworth

Use apps like skinseed for [iOS](https://itunes.apple.c m/us/app/skinseed-skin-creator-skins/id675628523?mt=8) or [Android](https://play.google.com/store/apps/details?id=com.africasunrise.skinseed&hl=en) to explore the identity of famous artists connected to the Whitworth collections and exhibitions

##Tools & Resources

###Projects

[Minecraft Education Edition](http://education.minecraft.net/resources/)
List of [Minecraft projects from Ross](http://cheapjack.github.io/EverythingMinecraft.html)
[CloudMaker](https://github.com/cheapjack/CloudMaker/)
[Printcraft](http://www.printcraft.org/)
[stuffaboutcode](http://stuffaboutcode.com)


###Pocketmine

[Pocketmine server software](https://www.pocketmine.net/)
[PaintMyLawn](https://github.com/shoghicp/PaintMyLawn)

###Further Reading 


