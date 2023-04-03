# About this project
Bypass check if user has a real microsoft account linked with the launcher<br>
⚠️ This is for entertainment purposes only ⚠️
# Before installation
If you have some accounts saved then executing this script will remove them!<br>

# Usage for PrismLauncher
Download the latest version of PrismLauncher from https://prismlauncher.org/, install it then go in terminal and execute this command:
### Windows CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > %appdata%/PrismLauncher/accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PrismLauncher/accounts.json
```

# Usage for PolyMC
Download the latest version of PolyMC from https://polymc.org/, install it then go in terminal and execute this command:
### Windows CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > %appdata%/PolyMC/accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PolyMC/accounts.json
```

# Usage for Portable versions
Download the portable version of PolyMC or Prism Launcher then execute this command in terminal:
### Windows Portable (cd to installation path) CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > accounts.json
```
### Linux Portable (cd to installation path) Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > accounts.json
```

After that you can create an offline account in the launcher. 
# What not to do
Don't delete the default offline account before you create a new offline account!

# BRO, I DON'T TRUST YOUR SCRIPTS!
Ok, if you know how to use a computer then there is an easy way. There is a file in repo called "accounts.json" and you need to download it to this place:
### Prism Launcher
* Windows: `%appdata%/PrismLauncher/`
* Linux: `~/.local/share/PrismLauncher/`

### PolyMC
* Windows: `%appdata%/PolyMC/`
* Linux:  `~/.local/share/PolyMC/`

### Portable
In the root directory of the installation... bruh
