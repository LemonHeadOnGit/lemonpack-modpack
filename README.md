# WELCOME TO THE LEMONPACK REPOSITORY

<p align="center">
    <a href="https://github.com/LemonHeadOnGit/lemonpack-modpack/issues" alt="Issues">
        <img src="https://img.shields.io/github/issues/LemonHeadOnGit/lemonpack-modpack" /></a>
    <a><img src="https://img.shields.io/badge/Version-v0.3.1-important" /></a>
</p>

This repository stores the JAR files, config files, and any other necessary files that makes the modpack what it is.

### THE REPOSITORY IS STILL IN EARLY STAGES, SO NOT EVERYTHING IS HERE YET.

---

### ` YOU ARE CURRENTLY ON THE SERVER VERSION OF THE MODPACK `

---

The server version of the modpack doesn't have any performance mods, however, all these mods were able to run at good performance with this configuration:

| SETTING | CONFIGURATION |
| ------- | ------------- |
| RAM (ALLOCATED) | 3GB   |
| CPU     | 2.8 GHz Intel Core i7 (LATE 2011) |
| RENDER DISTANCE | 4 CHUNKS |
| MAX PLAYERS | 5         |
| NETWORK SPEED | ± 2MB/s |

The ```server.properties``` file is equipped to handle this configuration.

### A file called ```startcommands.txt``` includes recommended java flags and minimum memory requirements to run the forge.jar server file.

> Keep in mind, you are able to modify the startcommands file in any way you want. If you don't know what you're doing, I recommend changing only the -Xmx and -Xms flags accordingly. In this case, `-Xmx/s3072m` means that the minimum and maximum amount of RAM that can be allocated is 3072MB (or 3GB).

>The `nogui` flag means that the server interface will not appear, and you will have to use the commandline for everything. Keeping this flag means that less system resources will be used, since the system doesn't need to draw a GUI.

## INSTALLATION

#### To install and run the server modpack, make sure that you have the minimum requirements (as seen in the table above).

#### This tutorial will NOT cover port forwarding. See `HOSTING.MD` to find out more.

Step 0. Download the repository, and extract the repository to any folder you want. 

Step 1. Download the Minecraft 1.12.2 server file, and the Forge 1.12.2 server file.

Step 2. Place both downloaded files in the modpack folder. Now, run the Minecraft 1.12.2 server JAR. Once the eula.txt file appears, follow the instructions in the file.

Step 3. Run the Forge 1.12.2 installer file, and choose `Install Server`. If necessary, change the installation directory to the modpack folder.

Step 4. Once the installation is complete, open the `startcommands.txt` file, as well as a Terminal/Command Prompt window. Next, in the command processor window, type `cd PATH/TO/MODPACK/FOLDER`, replacing "PATH/TO/MODPACK/FOLDER" with the actual path to the modpack folder.

>Note: Terminal is for Mac/Linux users, while Command Prompt is for Windows users. For Windows users, change the forwardslashes to backslashes.

Step 5. Copy all the text from `startcommands.txt` into the command processor window. It is recommended you change any necessary flags in the text file first, since you can always copy and paste the text from the text file. When you are ready to run the server, make sure all the text is in the command processor, and press the [Enter] key.

>Note: The `-jar forge.jar` flag is meant for the forge.jar server file, not the forge installer file. If the installed server file is not forge.jar, change the forge.jar text to the actual name of the installed server file.

>Important: DO NOT delete the original vanilla 1.12.2 server file. Deleting this will prevent the forge server from running, since it relies on the vanilla server file.
