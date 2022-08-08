# README

SERVER ADDRESS: *class-walt.craft.playit.gg*

## HOSTING SERVER - *Instructions*

Ensure `git` is installed by typing `git --version` in a command prompt.

Clone the repository with the following command:

```bash
git clone https://github.com/collinjones/MC-Server-1.19
```

### Mac OS
Navigate to where you cloned the directory in a terminal window and run the following command:

```bash
./run.sh
```

### Windows 10 / 11
Navigate to where you cloned the directory in Windows Explorer and run the file `run.bat`

## Pulling and Pushing Changes

Remember to always pull changes before running the server, and to always pull beforing pushing any changes. 

run `git pull` in your command prompt from the server directory to pull from the repo. 

To push your changes, close the server and run these commands from the server directory:

```bash
git add *
git commit -m "<Insert message>"
git push 
```


## JOINING SERVER - *Instructions*

### Setup instructions:

Clone the repository. 

1. Close Minecraft

2. Navigate to the cloned directory and run `forge-1.19-41.1.0-installer.jar`

    2a. Choose 'install client', select OK

3. Extract contents of the mods folder into your mods folder

    3a. Delete the cloned repository. 

4. Run Minecraft launcher. Select `forge 1.19-forge-41.1.0` to left of play button.

5. Add server class-walt.craft.playit.gg
