# Minecraft FAQ

A 101 on just some of the incredible Education related work in Minecraft and some links to resources and information

**Minecraft** is an open blocky sandbox game where your game `client` (a programme or Application on your computer/smartphone/tablet/console) connects to a Minecraft `server` somewhere on the internet or uses an internal or local server (on your machine or one nearby) and allows you to build things inside the game `maps`. 

Any glance at the first page of youtube will tell you what you could build.

Minecraft is a phenomenon; perhaps the greatest indie game success story of all time. A small game made for fun by some friends ended up being sold to MicroSoft for $2.5Bn and spawned a range of subcultures of all ages. 

The game is being used everywhere and for everything from [re-designing towns in Africa and mapping earthquake damage](http://blockbyblock.org/), launching official [Ordnance Survey Data](https://www.ordnancesurvey.co.uk/innovate/developers/minecraft-map-britain.html) to the [International Space Station](https://astro-pi.org/competition/winners/).

### A Brief Overview of Minecraft and it's many forms

#### Plaforms

Minecraft is on almost every popular platform, ie type of computer or Operating System you can think of! It's worth noting that they are all different and PC/Mac/Linux users cannot play on the same servers as say XBOX or PS4 players except in Windows 10. Each platform has its own type of server software distinct to each platform. 

 * PC/MAC/Linux (very customisable & cross compatible)
 * XBOX (non-customisable)
 * PS4 (non-customisable)
 * Raspberry Pi (very customisable)
 * iOS (very customisable)
 * Android (very customisable)

Its also a very customisable game, known in minecraft as 'modding' 

#### Custom servers like 

 * [Printcraft](http://www.printcraft.org/) 3D print your minecraft creations
 * [QCraft](http://qcraft.org/about/) Quantum Blocks!
 * [ComputerCraft](http://www.computercraft.info/)

#### Custom maps 

 * [TATE Britain](http://www.tate.org.uk/about/projects/tate-worlds-art-reimagined-minecraft)
 * [Ordnance Survey of Great Britain](https://www.ordnancesurvey.co.uk/innovate/developers/minecraft-map-britain.html) 

#### Custom Clients

 * [BiblioCraft](http://www.bibliocraftmod.com/origin-story/)

## Getting started playing Minecraft: Pocket Edition

 * Buy it for your device or book and use the Whitworth iPads

### Logging onto an external server

 * To get onto a specific server address like `whitcraft.uk` you need to:

<img src="https://cloud.githubusercontent.com/assets/128456/12626078/aedc529c-c52e-11e5-8882-9ffcf931862e.png" width="300">

Click on the `Play` Button on the start screen

<img src="https://cloud.githubusercontent.com/assets/128456/12619684/0545b2fe-c511-11e5-8a8d-1facd79c3239.png" width="300">

You will see a list of servers or an empty list if its your first go. Click on the `New` button

<img src="https://cloud.githubusercontent.com/assets/128456/12626160/31a1aaf6-c52f-11e5-9ea0-f56a0f2fe806.png" width="300">

Then Click on the small external server button to the left of the `Advanced` button 

<img src="https://cloud.githubusercontent.com/assets/128456/12619687/054ac244-c511-11e5-8817-57e4cac7666a.png" width="300">

You will see an empty `Name` and `IP/Address` table with the standard `Port` of `19132`.

<img src="https://cloud.githubusercontent.com/assets/128456/12619686/0549f616-c511-11e5-8ecf-0718b6c8c1e0.png" width="300">

Click on each entry in turn until your settings look like the above.

 * `Name` is a memorable name for the server you want to connect to
 * `IP/Address` is the actual address of the server which could be a number like `192.168.0.2` or an address like the Whitcraft server address `whitcraft.uk`
 * `Port` is the port number of the server. Sometimes the same address can use different post numbers so make sure it correct. `19132` is the standard port, so in the WhitCraft case change it to `19135`. Server addresses are sometimes written like this `whitcraft.uk:19135` which means `<IP/Address>:<Port>`
   * NB the `< >` means replace with the string or number you require

Thats it! Click `Add Server` and then click on the server you want to play. If it's running and you have correctly inputted the address and port nuber *exactly8 you will be able to login. Anyone can play on the `whitcraft.uk:19135` server from anywhere with a strong wifi connection; Even 4G is not stable enough to connect to an external server.

The `whitcraft.playat.ch:19135` server is white-listed and authenticated to the Whitworth iPads only and cannot be accessed outside the Whitworth Art Gallery.


## Getting Started modding

I recommmend starting with setting up either a simple pocketmine server or using the Minecraft Pi Edition with a Raspberry Pi 2.

### Pocketmine

[Pocketmine](http://www.pocketmine.net/) is what the Whitcraft resource is built in but its pretty easy to download the server software run it and then mobile devices on the same network as you (you will need to find the [ip address](http://touch.whatsmyip.org/) can connect to your server locally (not on the wider internet). 

We will add a brief guide here but you can find out how to setup a quick basic `vanilla` pocketmine server on the main pocketmine website above. You can even set a pop-up server on an Android smartphone in a forest clearing like Ross Dalziel is doing for the [DEADWOOD](https://github.com/cheapjack/DeadWood) project

Then build worlds relevant to you and your cohorts!

### Getting Started with a server

Read these detailed tutorials here 
http://pocketmine-mp.readthedocs.org/en/latest/

You also do need PHP5 installed correctly which you can get from here
 
http://pocketmine-mp.readthedocs.org/en/latest/installation.html
http://pocketmine-mp.readthedocs.org/en/latest/update.html


### Pop Up servers outdoors

<img src="https://lh5.ggpht.com/hzBT0nCoZAWZbicRnRV17SI-n6XwVPHv0EhYkHN_Ycs2Yg4ZxujMb-svCx1Ch8mkyME=w300" width="200">

You can use the [Pocketmine-MP Server App for Android](https://play.google.com/store/apps/details?id=net.pocketmine.server) app to run a simple server on an Android device. It needs to be a fast phone to cope; dual or quad core processor the latest MOTO E would do it, approx £80 phone.

You can then connect to this over a wifi hotspot and you've got a roaming hot-spot server! See the example below.

#### Example


[DeadWood](http://github.com/cheapjack/DeadWood) is a pop-up Minecraft server exploring Microscope slide images of Bacteria sampled in Grizedale forest. 

 * Used the [PaintMyLawnPlugin](https://forums.pocketmine.net/plugins/paintmylawn.646/) to import the images from a professional microscope camera in a makeshift lab in Grizedale visitor centre 
 * Used the [Pocketmine-MP Server App for Android](https://play.google.com/store/apps/details?id=net.pocketmine.server)
 * Imported a flat world into the Android Pocketmine app
 * Imported the latest **bleeding-edge development** build of [PocketMine-MP.phar](http://jenkins.pocketmine.net/job/PocketMine-MP-Bleeding/)
 * Started a WiFi hotspot on the Android device
 * Connected an iPad running `v0.13.1 alpha` version of Minecraft:Pocket Edition to said hotspot
 * started the server on the Android app
 * Pressed `Play` on iPad Minecraft app
 * Explored a virtual bacterial sample in the forest where it was sourced! Microbiology in Mincraft! 


### Minecraft Pi Edition and `mcpi`

You can also use the Minecraft Pi Edition for the Raspberry Pi and use the excellent [Adventures in Minecraft](http://eu.wiley.com/WileyCDA/WileyTitle/productCd-111894691X.html) book to use the `mcpi` API (Application Programming Interface) to make python code that can make interesting stuff happen on Minecraft servers.

One of the things I've been doing is setting up a FREE to play Minecraft server [CloudMaker](https://github.com/cheapjack/CloudMaker/) for FACT in Liverpool which is a space to play and explore using Minecraft as a learning platform for MAC/PC/Linux platforms..

You can find out more about that from the CloudMaker repository link above.

### The Minecraft Education Community

There's an emerging network of freelancers, organisations, artists, educators and creative technologists exploring the learning potential of Minecraft. The work I do in the game is all about exploring how we share and produce knowledge in a post-internet society and reflecting on early technological history and what tools are and are becoming.

You can see my twitter list of people here](https://twitter.com/cheapjack/lists/minecraft/members) and there's a great list of links and people on the TweachCode [Minecraft related twitter stream](https://twitter.com/search?f=tweets&q=tweachcode%20+minecraft&src=typd). 
 
