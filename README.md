
# How to Emulate PlayStation 3 games and play with friends online!

This is an in depth full tutorial I am making for friends to be able to set up RPCS3, a PS3 emulator to be able to install and play whatever games you would like to (online and locally!)

This goes over the setup for RPCS3, registering for online, where to find games, and how to set up Parsec, a remote play utility for connecting to friends' computers to play games with them.



## DISCLAIMER
I do not condone piracy to obtain your PS3 games, it is recommended to dump your existing, pre-owned games through a homebrewed system. Homebrewing on an existing system is its own very in depth process that I am not going to go over here, I am simply providing the knowledge of what I have learned over my time setting up my own system. I do not host any websites, files, or programs recommended in this tutorial.


## Features

- RPCS3
- Downloading Games (JDownloader)
- Remote Play (Parsec)
- Playnite (Game Launcher, optional)


## RPCS3

1. Begin by going to RPCS3's website and downloading and installing the correct program for your OS.
 https://www.rpcs3.net 

2. You will need the firmware update from Playstation's website for the PS3 emulator to function correctly.
https://www.playstation.com/en-us/support/hardware/ps3/system-software/
Scroll down the page and find "Update using computer", select it, and start your download of PS3UPDATE.PUP

3. Open RPCS3, close the launch window, and select file. From there, select install firmware, select your PS3UPDATE.PUP, and let it install and compile the caches afterward if it does it after the install automatically.

Congratulations! From there, the emulator is ready to launch any programs. You can open the config from the top bar of the window to configure controllers, change graphics settings, and more.

# Networking

Networking is very simple. Simply click Configuration, scroll down the list to RPCN, select it, and follow the prompts to register an account. You will need to confirm your email for it to work correctly. 

## Downloading Games

Once again, it is always recommended to dump games from a homebrewed PS3! There are a plethora of tutorials on the internet, but I recommend following the PSX-Place forum. They have tutorials, homebrewed applications, and more. It's hard to mess up if you can read.

If homebrew dumping isn't an option for you, then there are a few options. I recommend using the website https://nopaystation.com or using the R/Roms Megathread links. They are 100% safe to use. It is recommended to use an internet download manager. I recommend using JDownloader, an open source and FREE software that makes managing files and downloading quick and easy.
https://jdownloader.org/download/index all you have to do is right click any download link and hit 'Copy Link' and it will add it to a list of pending downloads that you then only have to hit start and sit back while it goes to work.

# NoPayStation 

NoPayStation is an open source repository for all PS3, PS1, and PS Vita games. Downloading games through this method is simple, just click search, type in the game that you want, click your region, hit enter. There is a chance that it may not be in the library, and if that is the case, then refer to the R/Roms Megathread method.

Once you have found your game, click on the name of it. You'll be presented with an option of downloading the .pkg file and downloading the .rap file. You need to download both of these files. the .pkg file is required to install into emulator for your game to exist, and the .rap file is required to install into the emulator so the software recognizes that you own the software you are attempting to open.

Once you have downloaded both your .pkg and .rap files for your game, simply drag and drop your files over the open RPCS3 window and select install. Once it's done, you should be able to open and play any game you install with this method. It works for any DLCs found in the repo too.

# R/Roms Megathread

https://r-roms.github.io/

This repository contains the files for more than just the PS3, but today that is what we are going over. At the top, select Sony, and then scroll down to the Playstation 3 games. There are two different hosts for each one, Myriant or Internet Archive. Myriant doesn't require an account and has unrestricted download speeds, while Internet Archive requires a free account just to protect their servers from being overwhelmed. I use each of these interchangably, so choose at your own needs.

Right click the name of any game you would like to download, click copy link, open JDownloader, and hit the start button. It will begin to download the .rar files you selected, and will automatically extract them. 

Once your downloads are finished, open RPCS3, select file in the top bar, and then click add games. A folder selection window will appear for you to navigate to the directory of your extracted folders, select those and click add. It will automatically populate your games. With this method, you don't need to worry about .rap files as the software will believe it is a disc game and will let you play it. 

I haven't tested DLC installation through these two sources, as most don't come with .rap files, so it may or may not work there. Looking through NoPayStation is always a good bet to find any DLCs you may want for your games.


## Parsec

This is easier than it sounds! Simply go to Parsec's website, create an account, and download the program for your OS.
https://parsec.app

Once you have created an account and installed the program, simply open it.

If you are hosting, hit share, and send your link code to your friends.

If you are connecting, take the link code you received and enter it in at the bottom right corner of the screen.

Congrats! You're connected and should be able to use your controllers as fit. Configuration in RPCS3's controller tab is required for the extra controllers, but is very easy and straight forward to do.


## Playnite

This part is completely optional, but is very nice to keep all of your installed PC games, as well as emulated games in the same place. It is an open source program full of optional addons and themes to customize your experience.
https://playnite.link

Install the program, open it and go through the initial setup, connecting any accounts you would like to, each connection adding the games to your library.

Once done with the initial setup, click the controller in the top left corner, hover over library, and select configure emulators. 

A window will open, select import at the bottom left. Here, navigate to the install folder for your emulator, which should be C:\Users\%USER%\Documents\RPCS3 if you didn't select a custom installation location.

Select the folder, and let it scan. It should automatically find your emulator, hit continue and close the configure emulator screen.

From there, click the controller again, add game, and then emulated game. select your emulator, and then for the directory, choose either your extracted folder, or if you installed the packages and .raps, your RPCS3 directory. It will automatically scan your folders and find your games!