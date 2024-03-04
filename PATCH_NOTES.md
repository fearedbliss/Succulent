# Patch Notes

This will contain a log of the patch notes as changes are made over time.

## 2024-03-04-0800

- Fixed a graphical bug where I forgot to update the Visual Progress Indicators
  on **800x600** resolution.

## 2024-02-12-2000

- Reverted the stack sizes for Arrows, Bolts, Keys, and Throwing Weapons back to their Vanilla values.
- The items that Fara (Act 2) and Ormus (Act 3) sell are back to Vanilla.

## 2024-02-11-2100

- The Experience Bar now has Visual Progress Indicators. Thanks to SierraIndustries for this.
  I extracted the needed portion from his [Hellfire II: Lazarus Mod](https://www.moddb.com/mods/hellfire-ii-lazarus-beta-4-062113-release).
  Please show him some support by checking out his mod.
  
## 2024-02-11-0045

- All item affix possibilities are back to Vanilla.

## 2023-11-22-2000 (BREAKING CHANGE)

This is a breaking change primarily because the stash size is returning back to Vanilla.
If you are an existing player, please move your items within the original game boundaries
or you will loose items during the migration. If you like using muling applications, then
this change should help retain compatibility with them. However, I'm not guaranteeing
compatibility with external applications since Succulent is an independent mod, and I want
people to use as little external tools as possible in order to increase game stability
and easier maintenance. With that said, here are the patch notes:

- The game stash sizes are now back to Vanilla for both Classic and Expansion.
- The Expansion Whirlwind skill is now back to Vanilla.
- The Expansion Static Field skill is now back to Vanilla.
- Vendor repair costs are now back to Vanilla.
- The rerolling Magic item recipe now also requires a Stamina Potion.
- The rerolling Rare item recipe now also requires an Antidote Potion.
- The skip introduction cinematics fix has been re-written. It will now skip the
  intros but still show the initial trademark screen.
- Grand Charms can now spawn as Rare items.
- The Affix system is now fully unlocked for all items in the game. This means that any
  affix can spawn on any item, including weapons, armors, rings, amulets, charms
  (of any size), and jewels. An affix can spawn on any item even if it doesn't make sense.
  Leveraging the full power of the RNG. There are no restrictions. The possibilities are endless.
- Rarity levels for all items are back to Vanilla.
  
## 2023-11-20-2000

- The recipe for 3 amulets -> 1 ring and 3 rings -> 1 amulet will now create its new item
  with an item level equal to the character level. Before it was 75% cLvl, now it's 100% cLvl.
- The recipe to re-roll a magic item and rare item has been re-introduced but significantly better.
  The recipe requires 3 perfect gems of any type and the item in question. The item will be re-rolled
  with an item level equal to 100% of the current item level + 10% of the player level. So you can slowly
  snowball the iLvl up, if you are willing to sacrifice many gems. It's better to just continue to farm
  higher item level items and use the 10% as an additional boost. At cLvl 90, you will get the maximum
  benefit of 9 additional iLvl boost to the existing item.
- The add socket recipe has been changed to require one less gem and now requires a thawing potion.
  This avoids confusion when adding a socket or rerolling (since before 3 gems re-rolled the item and
  4 added a socket!). As a benefit of this, adding sockets is slightly cheaper. Enjoy.

## 2023-11-20-0830

- Some Main Menu backgrounds have been improved to include the LOD logo.
- The character creation screen now is darker. Eliminates the "Amazon on Box" situation and improves horror feeling.
- The ambiguity between the number **`5`** and **`6`** has been fixed (again).

## 2023-11-19-2330

- The Main Menu screens are now back to the Original Classic Theme (with some customizations).
- The Main Menu now has a Darker Theme Song.

## 2023-09-14-1700

- Restored vendor base prices to their original values.
  - Vendor repair costs are still increased.
  - Gambling prices are still increased and flat.

## 2023-05-20-1200

- Adjusted Arrow and Bolt Stack Sizes to 250 (Max), 25 (Min), 75 (Spawn).
- Adjusted Key Spawn Stack size from 10 to 6.
- Repair costs have been increased.
- Restored the price of throwing weapons to their original values.

## 2023-05-19-1200

- Adjusted all gambling prices and are now using a rounded value.
- Gambling prices are capped at 2.5 million (The maximum amount of money you can have
  in your stash later in the game). Vendor prices can still go over this price.
- Gambling a Ring or Amulet now costs 100k (Up from 50k and 63k respectively).
- Increased vendor prices for all Armors and Weapons (Including Throwing Weapons).
- Rarity values have been flattened for all items in the game (Base Item Types, Set/Unique Items, Runes/Gems/Etc).
	- Roughly speaking, this means that when selecting an item, their relative rarity levels will be treated equally. This does not mean that the total probability is the same.
- You can now carry up to 500 Arrows, 500 Bolts, and 20 Keys per stack (Up from 350, 250, and 12 respectively).
- Arrow stacks can now spawn with up to 150 Arrows (Down from 200).
- Key stacks can now spawn with up to 10 Keys (Up from 6).
- The minimum amount that Arrow and Bolt stacks can spawn with is now 50 (Down from 100, and 60 respectively).
- All Throwable Weapons (Excluding Throwable Potions) now have the following stack values:
   - Maximum Stack Size: 250
   - Minimum Stack Size: 25 (10% of the Maximum Stack Size)
   - Can spawn with a stack up to: 75 (30% of the Maximum Stack Size)

## 2023-04-23-1930

- Completely remade, relooked, and improved the game's Treasure Classes / Drop Rates.
- Flawless Gems will now start dropping in Act 4 Normal.
- Act 5 Normal / Nightmare will start dropping Runes from the next difficulty.
- Gambling prices are once again a flat cost (not based on character level).
- Gambling prices have been increased.
- You can now once again leech life / mana from every monster in the game.

## 2023-04-21-2000

- Initial Succulent Release.
