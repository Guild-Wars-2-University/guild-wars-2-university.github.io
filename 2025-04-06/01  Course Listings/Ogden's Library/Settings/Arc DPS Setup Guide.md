ArcDPS is the DPS meter that most endgame players use.

It is useful to see how you are doing compared to the rest of the squad when it comes to DPS and when you start getting into endgame content DPS starts to matter, so it is important to know how to monitor yourself and others.

This guide assumes you are not using any other addon like re-shade or anything that affects graphics, as it could cause problems. There are workarounds, but they won't be covered here.

---

## Downloading and installing

Make sure the game is closed, then download ArcDPS from <https://www.deltaconnected.com/arcdps/x64/d3d11.dll>.
On certain browsers, you may need to press "..." in the download popup, then "keep", then "show more", then "keep anyway" in order to download it.
Once downloaded, place the file in the same folder as your Gw2-64.exe file, which is at `C:\Program Files\Guild Wars 2` by default, or can be found by right-clicking the game in steam and doing `Manage > Browse local files`.

---

## Opening it in game

Boot up the game and log into a character, then open the ArcDPS menu by pressing `ALT+SHIFT+T`. From here, tick "Area Stats" on the Interface tab, and this will open the basic DPS meter. Right click this new window and go to Display. In the "Stats format" bit, you can type in @<number> to change the display:

- `@1` = cleave total - how much damage you have done to all enemies 
- `@2` = cleave per second - how much damage you are doing per second to all enemies
- `@3` = cleave percent - what percentage of the squad's damage you are providing against all enemies
- `@4` = target total - how much damage you have done to the current target
- `@5` = target per second - how much damage you are doing to the current target
- `@6` = target percent - what percentage of the squad's damage are you providing against the target.

I like to have mine set to `@5 (@6)`, so that it shows my target DPS and the percentage of squad DPS I am doing.

On the Logging tab, set a logs folder (you may need to create this yourself, and can be anywhere on your PC) and set the path in the field at the bottom of it. Click the "Open" button to verify that the path is correct. You will need this later.

You you like, can add extra meters by clicking the "Extra Area Stats" checkboxes. Number 2 should default to breakbar damage. You can right click any window and go to "advanced stats" to change what sort of thing it monitors.

---

## ArcDPS Addons

There are a number of addons for ArcDPS, these are the ones I recommend getting:

- [Boon table](<https://github.com/knoxfighter/GW2-ArcDPS-Boon-Table/releases>) - Shows boon uptime of squad/party members
- [Healing Stats](<https://github.com/Krappa322/arcdps_healing_stats/releases>) - Show healing statistics
- [Killproof.me](<https://github.com/knoxfighter/arcdps-killproof.me-plugin/releases>) - Shows killproof.me stats of squad/party members

Simply download the .dll files from the releases page, and place them in the same folder as your `Gw2-64.exe` and `d3d11.dll` files (when the game is closed). They will be enabled the next time you launch the game.

---

## Keyboard shortcuts

- ArcDPS - `ALT+SHIFT+T`
- Boon Table - `ALT+SHIFT+B`
- Killproof - `ALT+SHIFT+K`

---

## Log Manager

Now that your logging is set up, you can download the [ArcDPS Log Manager](<https://gw2scratch.com/tools/manager>)

This is a self-contained program that doesn't need to be in the GW2 folder, place it somewhere you can remember. (This can be a subfolder inside the main "Guild Wars 2" folder from earlier)

The first time you fire it up, it will ask for the log location from earlier.
You can filter the logs based on failure/success, which wing/boss they are from, and also search for certain players and check logs from them. It's pretty easy to use, so have a play around with it.

The main use of it is uploading logs for you. Select a log you want to upload, and then just press the "Upload" button in the bottom right. It will take a few seconds, and then you will be able to press the "Open" button to open the log and read it.