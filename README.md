**Note: Rename the folder to OmniBar instead of OmniBar-MoP-main. Otherwise it won't work!**

# OmniBar - MoP
OmniBar is an _extremely lightweight_ addon that tracks enemy cooldowns. **Now for MoP!**

![OmniBar](http://i.imgur.com/p9DjSOh.png)

[Open a ticket to report any issues](https://github.com/ManneN1/OmniBar-MoP/issues)

[Submit a pull request](https://github.com/ManneN1/OmniBar-MoP/pulls)



## Features
OmniBar is easily customizable, and has a rich feature set.

### Customizable Cooldowns
Open the options panel to easily select which cooldowns you wish to track:

### Multiple Bars
Create as many bars are you want!

### Automatically Hide Icons
When a cooldown is used, its icon will be added to the bar. After it's complete, it will be hidden automatically. This allows more cooldowns to be tracked, while avoiding awkward gaps between bars.

### Show Unused Icons
Check this option if you prefer the icons to always remain visible. The **Unused Icon Transparency** slider will adjust the transparency of the unused icons. Check **As Enemies Appear** to only show unused icons for arena opponents or enemies you target while in combat.

### Track Multiple Players
If another player is detected using the same ability, a duplicate icon will be created and tracked separately.

### Profiles
Create custom profiles with dual specialization support.

### Cooldown Count
Allow Blizzard and other addons to display countdown text on the icons.

### Glow Icons
A glow animation will be displayed around an icon when it is activated.

_Note: This functionality does **NOT** work in the backport._

### Visual Tweaks
You can configure various visual tweaks such as size, border, ~~glow~~, transparency, columns, and padding. OmniBar also includes Masque support.

### Visibility
Choose to display OmniBar in arenas, battlegrounds, and world combat.

## Configuration
To open the options panel, type `/ob`

![OmniBar Options Panel](http://i.imgur.com/HTIe0h3.png)

## Backport Notes
This backport was developed in ~2 days.

* The spell list is from LibCooldownTracker (5.4.8), and I've made minor edit. It could be incorrect / improvements can be made, _feel free to create an issue or pull request if you have an improvment suggestion._
* In MoP, many talents, gear and glyphs impact CDs of spells (e.g. 4set Mage PvP set reducing Alter Time CD). I'm planning to add support for these, and where it is not possible to know the most common setup will be used (e.g. assume the target has 4set PvP bonus) these bonuses that impact CDs are/should be accommodated for. _Feel free to create an issue or pull request if you have an improvment suggestion._
* The animation flash / and target & focus highlight functionality does not work. Feel free to create a pull request for this. The issue lies in most of the xml shorthands not existing (e.g. atlas, and atlassize) along with some of the textures not existing in MoP.  
