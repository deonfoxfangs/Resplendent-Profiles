# Resplendent-Profiles
RebornBuddy OrderBot profile to obtain Resplendent Tools.

## Requirements
- The latest version of [LLamaLibrary](https://github.com/nt153133/LlamaLibrary)
- The latest version of [Lisbeth](https://lisbeth.io/downloads/EN/Lisbeth.zip)
- The latest version of [Exbuddy](https://github.com/Entrax643/ExBuddy)

## Required Settings and Warnings
- In Lisbeth, General > Disable Collectable Cleanup must be **CHECKED (ON)**. At one point in this profile it will put in multiple individual orders for crafting components B and C, and without this option Lisbeth will attempt to turn in collectables *after each craft*. This can be wasteful in teleport fees, and also highly sus. For similar reasons, consider deactivating Equipment Optimization to save time.
- Make sure your other Lisbeth settings are set appropriately - probably set up a Home point so you don't craft 24/7 in Eulmore, set up food/syrup, optionally set up masterpieces so you don't farm a billion Swallow Skins.
- Any Resplendent Tools you already have must be in your inventory or armory chest so the profile can see you have them and skip over them.
- You must have *at least* 110 or so inventory spaces available if Lisbeth is set to extract materia automatically (probably 105 if not). You may end up with 100 collectables in your inventory at some point during this process if starting fresh and if Lisbeth detects your inventory is full it will halt until rectified.

## How to Use
- Open "Resplendent Start.xml" in any text editor. Look for the various "ENTITY" entries that correspond to each DoH job. Set the value for each one to be 1 if you wish to obtain that weapon, and 0 if you wish to skip it. You don't have to set it to 0 for tools you already have, it'll see those and skip automatically.
- In RebornBuddy, select "Order Bot" as your botbase, then click "Load Profile." Load "Resplendent Start.xml"
- Wait for the profile to do its thing. It's pretty self-sufficient but do make sure to check up on it regularly as with any long-term botting profile.
