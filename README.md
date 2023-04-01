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
### Windows Portable (cd to installation path) CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > accounts.json
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
### Windows Portable (cd to installation path) CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > ~/.local/share/PolyMC/accounts.json
```

After that you can create an offline account in the launcher. 
# What not to do
Don't delete the default offline account before you create a new offline account!
