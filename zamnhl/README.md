# The Phoenix Project Software Playtester Resources
## Codename ZAMNHL — *"Half-Life: Zombies Ate My Neighbours"*
***Codename ZAMNHL*** is The Phoenix Project Software's latest advancement in game development. Making use of the **Half-Life Engine** and [**Grey Source**](https://moddb.com/engines/grey-source), it brings the player (that's you!) an amazing hectic combat, survival, stealth and puzzle solving experience.
![Screenshot of Codename ZAMNHL](https://media.moddb.com/images/members/5/4383/4382734/profile/unknown_1.png)


# How to Install
## Traditional download (easiest method)
1. Go to the [*Half-Life: Zombies Ate My Neighbours* developer repository.](https://github.com/phoenixprojectsoftware/zamnhl) If you do not have access to it, let the lead developer know in the Phoenix Discord.
2. Scroll down until you see **Releases** on the right hand side. Click the **Releases** link to find all the compiled builds of ZAMNHL.

3. Find the latest release with the tag **"pre-release."** It should display at the top. Do NOT download a version with the tag **"Latest release."**
4. Click the **Assets** button to expand its section. Then select **Source code (zip).** This will download the game in a ZIP file. When you open it after it downloads, it will have a folder called `zamnhl-VERSIONNUMBER` (obviously it won't say "VERSIONNUMBER," but the version you downloaded).
5. Rename the folder from `zamnhl-VERSIONNUMBER` to just `zamnhl` in the ZIP file.
6. Keep the ZIP open. Go into Steam, and find *Half-Life* in your library on the sidebar (if you do not own *Half-Life* on Steam, you will not be able to play ZAMNHL. [Buy *Half-Life* here](https://store.steampowered.com/app/70) if you don't own it). Right click it and select **Manage** and then go to **Browse local files.**
7. Drag and drop the `zamnhl` folder from the ZIP into the ***Half-Life* folder** and it should extract. When performing the drag & drop procedure, make sure that another folder or file is not highlighted.
8. Restart Steam and you should see ***Half-Life: Zombies Ate My Neighbours*** in your library. If you can't find it, try searching for it. If you still can't find it, you may have extracted the game incorrectly. Check with #playtesters-general in the Phoenix Discord and try the process again.
9. Run the game. Open the console by pressing the ` key (it is below Esc).
10. Enter this command: `version_greysource`  (if you are on version 2012 or later enter `version_adm`) and check with the lead developer in the Phoenix Discord to make sure it's the right version.
### How to update
Open the link provided to you in #playtesters-announcements and follow the download instructions above from step 4.
## Using Git (most recommended, but quite hard)
1. Right click *Half-Life* in your Steam library. Go to **Properties** > **LOCAL FILES** > **BROWSE LOCAL FILES**. Hold shift and right click, and select **Open command window here.** Enter `cd` in the CMD window and copy the path. Keep the CMD window open.
2. Install [Git.](https://git-scm.com/download/win) Keep all settings the same in the installer.
3. Go back to your CMD window to add your GitHub account to Git:
  - `git config --global user.name yourusername`
  - `git config --global user.email youremail`
4. Clone this repository:
  - `mkdir zamnhl`
  - `cd zamnhl`
  - `git clone https://YOURGITHUBUSERNAME:YOURPASSWORD@github.com/phoenixprojectsoftware/zamnhl.git .` (make sure you don't forget to add a dot at the end!)
5. Restart Steam and *Half-Life: Zombies Ate My Neighbours* should be in your library.

### How to Update
Go to your ZAMNHL folder and run the Quick Pull file. After updating, check the `version_greysource` output in the console. If the build number and/or date updated, it worked.

# Support
## Git
## I used the "Download ZIP" button from GitHub and now I can't update. What do I do?
Simply re-clone the game. Delete your current ZAMNHL folder and follow the installation instructions carefully.

## The game won't update.
This is usually due to a conflict issue. To do this, simply re-clone the game. Delete your current ZAMNHL folder and follow the installation instructions carefully.
