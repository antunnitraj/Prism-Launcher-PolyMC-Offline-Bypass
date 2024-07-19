# About this project
Bypass check if user has a real microsoft account linked with the launcher<br>
⚠️ This is for entertainment purposes only ⚠️

# These launchers are too complicated for me :(
You can try out my other project [Offline Minecraft Launcher](https://github.com/antunnitraj/OfflineMinecraftLauncher)

# Before installation
If you have some accounts saved then executing this script will remove them!

# How to use
- Install Prism Launcher or PolyMC
- Go through the quick setup
- Execute the command for the appropriate bypass (see [below](#usage-for-prism-launcher))
- Create an offline account
- Delete the "No Profile" account
- Set the newly created account as the default
- Enjoy!

# How does this work?
These launchers use a file called "accounts.json" which stores information about user's accounts. It also indicates whether a user owns Minecraft. This functionality allows players to play Minecraft even if they are offline, such as when playing on a Steam Deck in the middle of a forest. This feature can be exploited to gain access to the launcher and Minecraft's assets.

# Custom skins?
For that luxury you can use Ely.by skin system on the [ElyPrismLauncher](https://github.com/Octol1ttle/ElyPrismLauncher)

# What not to do
Don't delete the "No Profile" account before you create a new offline account, that will break it!

# Usage for Prism Launcher
Download the latest version of Prism Launcher from https://prismlauncher.org/, install it, go through the quick setup, close the launcher, then execute this command in the terminal:
### Windows CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > %appdata%/PrismLauncher/accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PrismLauncher/accounts.json
```
### Linux Shell (flatpak):
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/accounts.json
```
### macOS
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/Library/Application\ Support/PrismLauncher/accounts.json
```

# Usage for PolyMC
Download the latest version of PolyMC from https://polymc.org/, install it, go through the quick setup, close the launcher, then execute this command in the terminal:
### Windows CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > %appdata%/PolyMC/accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PolyMC/accounts.json
```
### Linux Shell (flatpak):
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.var/app/org.polymc.PolyMC/data/PolyMC/accounts.json
```
### macOS
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/Library/Application\ Support/PolyMC/accounts.json
```

# Usage for Portable versions
Download the portable version of [PolyMC](https://polymc.org/) or [Prism Launcher](https://prismlauncher.org/), run it, go through the quick setup, close the launcher, then execute this command in the terminal:
### Windows Portable (cd to installation path) CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > accounts.json
```
### Linux Portable (cd to installation path) Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > accounts.json
```

# Manual Installation
There is a file in the repository called [accounts.json](accounts.json) and you need to download it to this path:
### Prism Launcher
* Windows: `%appdata%/PrismLauncher/`
* Linux: `~/.local/share/PrismLauncher/`
* Linux (flatpak): `~/.var/app/org.prismlauncher.PrismLauncher/data/PrismLauncher/`
* macOS: `~/Library/Application\ Support/PrismLauncher/`

### PolyMC
* Windows: `%appdata%/PolyMC/`
* Linux:  `~/.local/share/PolyMC/`
* Linux (flatpak): `~/.var/app/org.polymc.PolyMC/data/PolyMC/`
* macOS: `~/Library/Application\ Support/PolyMC/`

### Portable
In the root directory of the launcher
