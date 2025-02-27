# Scout
[Modrinth](https://modrinth.com/mod/scout) | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/scout)

A mod focused on "physically" extending the inventory (adding slots) through wearing various types of bags. Heavily inspired by makamys' [Satchels](https://github.com/makamys/Satchels).

![Preview image of inventory with a pouch, an upgraded pouch, and upgraded satchel equipped](.assets/inventory_preview.png)

Items are retained on the bag items themselves. The bag items are equipped through [Trinkets](https://github.com/emilyploszaj/trinkets) slots. A new slot type for pouches is added, with two slots.

## Future Plans
- [ ] Satchel renders on the wearer
- [ ] 1.19.4 Build (Accepting PRs)
- [ ] 1.20.1+ Build (Accepting PRs)
- [x] ~~Tooltip preview of items inside bags~~

## Forge?
A Forge version is not planned. You are free to port it, but I will not endorse it.

## Credits
* makamys - Original inspiration from Satchels
* Emi - Trinkets
* Kat - Original pouch texture, taken from an older mod of mine and reworked for Scout

## Building
Due to using multi-projects in Gradle and the 1.19 version depending on the 1.18 version, you will get errors trying to build normally the first time.

1. Go into `settings.gradle` and comment out `include 'platform-1.19'`
2. Build the 1.18 version
3. Uncomment the include
4. You can now build the 1.19 version

Repeat everytime version is bumped.
