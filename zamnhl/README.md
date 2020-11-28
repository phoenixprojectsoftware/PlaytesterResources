# How to Install
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

# How to Update
Go to your ZAMNHL folder and run the Quick Pull file. After updating, check the `version_greysource` output in the console. If the build number and/or date updated, it worked.

# Support
## I used the "Download ZIP" button from GitHub and now I can't update. What do I do?
Simply re-clone the game. Delete your current ZAMNHL folder and follow the installation instructions carefully.

## The game won't update.
This is usually due to a conflict issue. To do this, simply re-clone the game. Delete your current ZAMNHL folder and follow the installation instructions carefully.