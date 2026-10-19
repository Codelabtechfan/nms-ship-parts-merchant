# Ship Parts Merchant (No Man's Sky mod) – by Cookie Gamer

The **Starship Technology merchant** on space stations (the one who sells Starship Reactors / reactor cores for Nanites) now **also sells regular Starship Fabricator parts**: Fighter, Hauler, Explorer and Solar ship cockpits, wings, engines, sails and so on.

- Everything he already sells (reactors, ship upgrades) **stays**. Parts are only added.
- **No Corvette modules** are added.
- Changes one file: `METADATA\REALITY\DEFAULTREALITY.MBIN` (`TradeSettings > ShipTechSpecialist > AlwaysPresentProducts`).

## Why is there a script and not a ready .pak?
Mods have to be built from your own copy of the game files, so this is shipped as an **AMUMSS script**. AMUMSS builds the mod on your PC and installs it in one go, and it keeps working after game updates.

## Install (about 10 minutes, done once)
1. Download **AMUMSS** from https://github.com/HolterPhylo/AMUMSS/releases (or its Nexus page) and unzip it somewhere simple, e.g. `C:\AMUMSS`.
2. Download `CookieGamer_ShipPartsMerchant.lua` from this repo's latest release.
3. Put it in `C:\AMUMSS\ModScript\`.
4. Double-click `BUILDMOD.bat`. Answer the questions:
   - Combine into one mod? Either answer is fine.
   - **Copy to the game's MODS folder? Y**
   - If asked for the game folder, pick it (Steam: `C:\Program Files (x86)\Steam\steamapps\common\No Man's Sky`).
5. Start No Man's Sky. If it warns about mods, accept. Go to a space station and talk to the starship technology merchant.

Tip: on Difficulty settings, set "Goods availability" to Abundant if not all parts show up.

## Remove it
Delete the `CookieGamer_ShipPartsMerchant` folder from `No Man's Sky\GAMEDATA\MODS`.

## After a game update
Run `BUILDMOD.bat` again.

## Credits
Ship part ID list based on AltF4's "Add Ship Custom Parts To Space Station Shop" script (AMUMSS script collection).
