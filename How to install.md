# How to install
~~I'm so sorry~~
These instructions are a little different than the usual modpack since a bunch of the mods that I wanted to use aren't available over CurseForge. So, things will have to be done a little differently, but hopefully with these instructions, you'll be able to get the modpack working!  

## Step one: Add the instance
Since this modpack isn't on any specific launcher, we have to add the instance to a launcher manually. I personally use PrismLauncher and I know that most people have the curse launcher installed, but I'm going to guide through the process for the official launcher because the process should be largely the same any way you do it, and this way is one that anyone can use.  

First, add a new installation by going to the 'Installations' tab and then clicking 'New installation'.  

Then, you need to change a few more things:  
- Set the version to `relese 1.7.10`
- Set the JVM arguments to `-XX:+UseG1GC -Xmx4G -Xms4G -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M`
- Finally, launch the game once. You can close it as soon as it's at the main menu. Make sure the launcher also closes too. 


## Step two: Download and install forge
This is step should be not too bad, but a little difficult to get the first time. First, go to [the page for Forge 1.7.10 1614](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.7.10.html) and download the Latest or Recommended version of Forge, they're both the same. Then, run the jar that you've downloaded. There might be an issue if you haven't run the instance of Minecraft in 1.7.10 before. Otherwise, it'll take a minute and then give a success message.  


## Step three: Download the mods and config
This modpack uses mods that aren't availabe from curseforge. This means that you have to download the mods from github. This is probably illegal, but for me, not for you. Simply click the link to the zip folder on the most recent release on [this](https://github.com/DrKittyKat/mmodpack/releases) page. I'll update this page with mods and config files as I change it. Inside will be a `mods` folder and a `config` folder. Extract these two folders into the folder `%APPDATA%/.minecraft/`


## Step four: Play?
That should be everything to get the modpack working properly. Feel free to DM me with any issues.  
<3