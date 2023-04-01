# About this project
Bypass check if user has a real microsoft account linked with the launcher<br>
⚠️ This is for entertainment purposes only ⚠️
# Before installation
If you have some accounts saved then executing this script will remove them!<br>
This is tested on PrismLauncher 6.3 and it works flawlessly
# Usage
Go in terminal and locate installation path of Prism Launcher then execute this command:
### Windows CMD:
```
echo {"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3} > accounts.json
```
### Linux Shell:
```
echo '{"accounts": [{"entitlement": {"canPlayMinecraft": true,"ownsMinecraft": true},"type": "Offline"}],"formatVersion": 3}' > accounts.json
```
After that you can create an offline account in the launcher. 
# What not to do
Don't delete the default offline account before you create a new offline account!
