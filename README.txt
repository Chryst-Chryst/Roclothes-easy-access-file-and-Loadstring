OPTION #1 -- original content file method
open roblox's file location and locate the "content" folder
put the ENTIRE "RClothesContent" folder into the roblox "content" folder, DO NOT put the assets of the folder into the roblox "content" folder
IGNORE EXTRACONTENT, IT IS NOT IMPORTANT

if you're using bloxstrap, locate the Modifications folder
if you dont see a "content" folder, create one yourself
!! WARNING: some bootstrappers like Fishstrap & Voidstrap have blacklisted .mesh files. DO NOT use these bootstrappers as it will not work as intended !!


OPTION #2 -- executor's workspace access
locate your executor's workspace folder (can be found within the executor's UI or files)
put the ENTIRE "RClothesContent" folder into the workspace folder, DO NOT put the assets of the folder into the roblox "content" folder


after installing the assets, use the script included in the ZIP, "roclothes v##.##.##lerp().txt"



# update log v0.7.9:lerp(.1)

- clothes -
- new clothing assets from galaracsha
  - Pussy Plaster
  - Boob Plasters
  - Nipple Heart Stickers
  - Gag w/ Blindfold

- new stuff -
script now accepts content folder being added into your executor's workspace
revamped HP system to not update constantly
- linked HP
  - currently only accessible via bundles (add LinkedHeal after HardcoreHP)
  - heals both TopHP and BottomHP simultaneously with hardcore (requires both to have a value)
- Favorite ClickExecute [WIP]
  - currently doesnt have a button to enable, must be enabled with the use of presets
  - using ClickExecute on NPCs will remember the NPC after it despawns and respawns, automatically applying on respawn

- bug fixes -
fixed method 2's teleporting issue (script works properly in games like Pillar Chase Recode)
fixed Remove Breasts not working with HPClothes
attempting to create meshes will now warn the player if something goes wrong
fixed most dynamic head's accessory scaling. use accessorysizelock if issue persists
small attempt to fix face toggle
breast clothing fixes related to HPClothes, should properly hide itself when ripped unless HPClothes is set to nil
added a warning for shirts & pants if theyre detected as invalid clothing assets instead of breaking the script
fix heads not changing color
saved keybind txt properly updates now when relaunched