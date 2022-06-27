# Reagan's Minecraft Server
Install guide and file repository for the necessary mods and programs needed to join the server. The server uses minimalistic plugins and mods so your performance won't be impacted no matter which OS you are using (talking about you Mac peasants)

## What you will need:
1. A Minecraft Account
2. The Minecraft launcher installed
3. Java 8 installed on your computer (can be accessed through here): https://www.java.com/en/download/manual.jsp
5. Maybe a brain

## Windows Install
### Files you need to download from the repo
1. ```voicechat-forge-1.19-2.2.45```. The ```voicechat-forge``` is a mod that is added to your game profile when you install the ```forge-1.19``` file.
2. ```forge-1.19-41.0.45-installer```
### Forge 1.19 install
Literally download the ```forge-1.19-41.0.45-installer``` and **_double-click it_**. 

Select **_Install Client_** and press "ok". See the image below

![Forge Link](https://i0.wp.com/www.alphr.com/wp-content/uploads/2021/03/1-32.png?resize=309%2C293&ssl=1)


### Adding the voicechat mod to your minecraft version
1. Download the file ```voicechat-forge-1.19-2.2.45``` and keep it easily accessible.
2. On the windows search bar type in ```%appdata%```. Hit enter to search.
3. Open up the ```.minecraft``` folder
4. Drag and drop / Copy and paste the ```voicechat-forge-1.19-2.2.45``` file into the **_mods_** folder.
   - If you don't have the mods folder create one inside the ```.minecraft``` directory. Make sure to call it ```mods```, it's case sensititive!!
   - If you have mods already inside this folder,  that aren't supported by 1.19 I would suggest removing them (e.g. the old voicechat file). 

### Final Steps
Start up the Minecraft Launcher, making sure to select the ```forge 1.19-forge-41.0.45``` as the current playable version. It should have automatically selected for you so all you need todo is press **_start_**. Happy mining!


## MacOS Install
Make sure you have installed Java 8 JRE, as this is essential for the ```forge``` install. You can get the java installer here at this link https://www.java.com/en/download/manual.jsp

### Files you need to download from the repo
1. ```voicechat-forge-1.19-2.2.45``` The ```voicechat-forge``` is a mod that is added to your game profile when you install the ```forge-1.19``` file.
2. ```forge-1.19-41.0.45-installer```
3. ```Minecraft_1.0.zip```

### Forge 1.19 install
As Mac users have fun fun times running downloaded files, do the following steps to open up the forge-installer:
1. **_RIGHT CLICK_** on the downloaded ```forge-1.19-41.0.45-installer.jar```
2. Open with ```Java Launcher (default)```

Select **_Install Client_** and press "ok". See the image below. Note the version listed on the image below is outdated, DO NOT WORRY if your forge version is different on your computer than on the image.

![Forge Image Linke](https://i0.wp.com/www.alphr.com/wp-content/uploads/2021/03/1-32.png?resize=309%2C293&ssl=1)

### Adding the voicechat mod to your minecraft version
1. Download the file ```voicechat-forge-1.19-2.2.45``` and keep it easily accessible.
2. **_Open Finder_** and press ⇧ Shift + ⌘ Command + G or open the Spotlight popup through the magnifying glass icon on the right of the Menu Bar.
3. Type ~/Library/Application Support/minecraft and hit ↵ Enter .
4. Create a ```mods``` folder within this minecraft directory. It is case-sensitive so please be aware.
5. Drag and drop / copy and past the ```voicechat-forge-1.19-2.2.45.jar``` file into this mods directory.
   - If you have mods already inside this folder,  that aren't supported by 1.19 I would suggest removing them (e.g. the old voicechat file). 

### Launching Up Minecraft
Unfortunately there is a bit of a bug with the VoiceChat mod, it requires admin permissions to launch up the application (at least for the good ol macs). And to this date there isn't an easy workaround (even if you try and elevate the appliction's microphone settings). I have however made a bootleg **work around**. 

Downloading the ```Minecraft_1.0.zip``` and extracting the zip (double clicking it) will give you a brand-new macOS minecraft application. This is literally a dummy app it holds no other purpose execpt to execute one line of code:

```/Applications/Minecraft.app/Contents/MacOS/launcher```

This script will automatically launch up the REAL minecraft launcher in admin mode. Thereby by-passing all those pesky microphone bugs. When the application is extracted from the .zip and turned into ```Minecraft_1.0.app```, you should be able to double-click that new app and it will auto-start the proper minecraft launcher. **_Problem solved_** phew.


