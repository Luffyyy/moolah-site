---
sidebar_position: 1
---

# Using FModel

## Setup FModel for PAYDAY 3
Open up FModel and Setup it for PAYDAY 3 by clicking `Directory` > `Selector`.
Then adding the name of the game (Doesn't matter how you call it) and **root** directory of the game.
![Setup Game](assets/fmodel-1.png)

As of writing, PAYDAY 3 uses an AES key so in order to access the game files, you need to give the AES key to FModel.
Open the menu for that by clicking `Directory` > `AES`.

![Setup AES Key](assets/fmodel-2.png)

That's it! You should now be able to access the game files without repeating this step.

## Exporting

Next, click on `Load` under the `Archives` tab (Make sure Loading Mode is set as `All`).
![Load Packages](assets/fmodel-3.png)

You should now see two folders, navigate through the PAYDAY3 folder and find which texture you wish to replace.
You can also press <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>F</kbd> to search for assets.
We'll export the phone screen texture (`PAYDAY3/Content/Environment/_Common/Interactable/MobilePhone_01/Component/T_PhoneScreenWithAlpha_`) 

Once you find the texture you wish to replace, right click on the file and click `Save Texture (.png)`.
FModel should print out a message on the console which let's you click to reveal where it saved the texture in.

![Export Asset](assets/fmodel-4.webp)

The process is very similar for other assets. For models you want to export to `psk`, animations `psa`.
In some cases you will need to export to raw data.