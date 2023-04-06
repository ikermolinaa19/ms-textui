## MS SCRIPTS - ms-textui

Redesign of the a-textui by Amvi#1784, this redesign has been done by Molina#6922

It is strictly forbidden to steal this script either by changing the name or removing the authors' names.

MS-SCRIPTS: https://discord.gg/BCrFN5QDZu


## Preview:

![image](https://user-images.githubusercontent.com/113800789/230480039-c2b38250-f839-47a0-8f2f-ebc8ff616949.png)


## How to install ms-textui?

The installation of this textui is very simple, here is a step-by-step explanation:

1. In the file en_extended/client/functions.lua replace line 95 to line 146 with this:

ESX.TextUI = function(text)
    return exports["ms-textui"]:showHelp(text)
end

function ESX.HideUI()
    return
end

ESX.ShowHelpNotification = function(text)
    return exports["ms-textui"]:showHelp(text)
end

ESX.ShowFloatingHelpNotification = function(text)
    return exports["ms-textui"]:showHelp(text)
end

2. Add the ms-textui to your resources folder and make sure to put ``ensure ms-textui`` in your server.cfg.

3. Restart your server and enjoy our textui
