# Primitive Tools

A mod for Vintage Story to allow stone versions of hammer, pickaxe, and log splitter.

## About

I felt like smoking meat for long term food preservation was a must-have ability in the Stone Age, to help prepare for first winter.  I had found [Primitive Survival](https://mods.vintagestory.at/primitivesurvival), which includes a smoker, but I needed boards to make it.

In vanilla Vintage Story you can't make boards until you make a saw, and you can't make a saw until you enter the Copper Age.

So then I found this mod, [Primitive Tools](https://mods.vintagestory.at/primitivetools), made by Zinth and released on the Creative Commons license.  I took that mod, fixed the errors, stripped out the parts I didn't like and present it as modified here in this Github repo.

## Changelog

```
v1.0.0 - Initial release of Primitive Tools.
v1.0.1 - language file update
	- added ReadMe file to mod package for "professionalism".
	- fixed en.json to work propperly - all items added by this mod should have propper names now (Stone Pickaxe, Stone Hammer, Wood Splitter, etc. . .)
	- added Ukrainian, Russian, and Japanese Google translated language translation. - Please let me know if something translated wrong!
V1.2.0 - Ground Storage Update
	- added the ability to store all 3 tools on the ground.
	- added the ability to store all 3 tool heads on the ground.
	- added German Translation, thanks to ThePionier for translating it.
	- fixed typo in handbook attribute. Handbook should no longer show all varients of the tools when looking at the recipe.
	- removed some ironias texture files I forgot when I was going make the wood splitter make splintered wood planks instead.
V1.3.0 - Bone Arrow Update
	- Added bone-arrows and bone-arrowheads. Should be compatible with all other arrow mods (note: damage is based on vanilla values so will be pointless if you use the Bullseye mod by Rahjital, but is still compatible.)
	- Bone Arrow damage falls between copper(0 added damage) and flint(-0.5 added damage) added damage doing -0.25 damage with a 0.2 chance to break. This makes it a good step before getting metal while keeping it balanced with the default game.
	- Added bone-arrowhead recipe using the splitter and a bone to make 4 bone arrowheads. (may look at adding a new tool for this later)
	- Added bone arrow recipe.
	- Updated language files to support the new items.
	- Added grass rope recipe 15 dry grass to make 1 rope (may need balance tweaking)
V1.3.1 - Bug Fixing
	- fixed hitbox on all placeable tools and parts. So you can now pick them back up!
	- added ability to store up to 4 toolheads on the ground.
	- added ability to store 4 bone arrow heads on the ground.
	- fixed compatiblity with Weaponpack Gamma by Mr1k3
	- changed modinfo to be inline with expected formating.
V1.3.2 - Localization Fix
	- fixed bug causing it to crash when using several of the localiztions
	- updated to main gamer version 1.18.0
V1.4.0 - On Fire
	- Changed english translations to exclude the knapping discrption
	- Removed my custom rope texture and replaced with official rope texture on all tools.
	- Added item resource Twig (crafted from a stick)
		- Twigs burns for 1 seconds at 700 degrees. (Stick burns 8 seconds at 700 degrees.)
	- Added item Twig Bundle  (Crafted from |3 grass| 6 twigs| 3 grass|)
		-Twig Bundle burns for 18s (firewood burns for 24s) at 700 degrees (same as firewood and sticks)
V1.4.1 - Bug Fixes
	- Fixed twig bundle item name.
	- Reverted Vintage Story required version back to 1.16.0 for backwards compatability.
	- Added Lang suport for Portuguese (Credit: Yanazake)
	- Updated all previuosly supported language files with google translated descriptions for the twig and twig bundle.
V1.5.0 - Forked
	- Removed bone arrows and twigs (fixing errors)
```

## Credits

All this code was done by [Zinth](https://mods.vintagestory.at/primitivetools), I just fixed the errors.