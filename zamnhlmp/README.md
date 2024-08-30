# The Phoenix Project Software: Playtester Resources
# How to Install ZAMNHLMP Dev Branch (Public PlayTest PPT)
## Creating your GitHub account
In order to proceed it's recommended that you create a [GitHub account.](https://github.com/signup)
## Downloading GitHub Desktop
Though you can just use a CLI, GitHub Desktop is the easiest way to install and update ZAMNHLMP Dev. To install GitHub Desktop, [click here.](https://desktop.github.com/download/)
## Installing *Half-Life* on Steam
Open your Steam library and [install *Half-Life.*](steam://install/70) Ensure the game is not set to the `steam_legacy` branch. Once the game is installed, right-click it in your library menu and go to **Manage > Browse Local Files.**
![enter image description here](https://imgur.com/LZo78pK.png)

This will open a File Explorer window to your local *Half-Life* install directory:
![enter image description here](https://imgur.com/ioxtTmW.png)

Click the blank space in the file-path to the left of the search box, and the space will become typeable. Copy the path to your clipboard; in most cases it's `C:\Program Files (x86)\Steam\steamapps\common\Half-Life`.

## Cloning ZAMNHLMP
Now, you can clone ZAMNHLMP from The Phoenix Project Software. Open GitHub Desktop and sign in with your account.

On the intro screen, click "clone a repository from the Internet" and go to the URL tab to enter the following in the URL box:

`phoenixprojectsoftware/zamnhlmp`

And in the **Local path** box, paste your *Half-Life* install directory and add to the end of it `zamnhlmp_dev`, so it SHOULD look [something] like this:

`C:\Program Files (x86)\Steam\steamapps\common\Half-Life\zamnhlmp_dev\`

If it's all correct click **Clone** and wait for the process to finish.

![enter image description here](https://imgur.com/49L59Ng.png)

## Setting the dev branch
When the clone has finished, you'll see a screen like this:
![enter image description here](https://imgur.com/qZJvmCl.png)

To switch to the `dev` branch and play the correct PPT version, go to the **Current branch** button at the top, and select **origin/dev.**
![enter image description here](https://imgur.com/sEUvP0k.png)

Then, at the very top of the Window, go to **Repository > Pull** to download the latest changes. The process shouldn't take too long.

![enter image description here](https://imgur.com/xiGZm9B.png)

## Opening the game
Restart Steam by going to the icon in the system tray and clicking Exit, or the top left Steam dropdown box in the main window. Once restarted, you should see ***Phoenix Developer - Half-Life: Zombies Ate My Neighbours Multiplayer*** in your library. Open it, and you should see the game's main menu screen. ZAMNHLMP Dev is now installed.

# Updating the game
At the very top of the GitHub Desktop Window, go to **Repository > Pull** to download the latest changes. The process shouldn't take too long.

![enter image description here](https://imgur.com/xiGZm9B.png)
