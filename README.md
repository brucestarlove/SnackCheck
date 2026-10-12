# Snack Check

Two buttons: one eats, one drinks. They always grab the best food and water in your bags, so you're not digging through them after every pull. It also tells you when you're running low, before you end up sitting there with nothing left.

Made for WoW Forever.

## What it does

It picks the highest level food and drink your character can actually use. Leftovers from an older stack go first, so your bags don't fill up with stacks of 2. Buff food never gets eaten unless you tell it to.

Got mage food or water? That goes first, even before something you pinned. Free food is free food. If you're the mage yourself, the warnings keep an eye on your conjured stuff instead and tell you when it's time to conjure more.

Hover over a button and you get a list of everything in your bags. Click one to always use that, click it again to let the addon pick. When your pinned food runs out it just uses the next best thing, and switches back once you've restocked. Pins are per character.

You get a warning when the food or drink you're about to use drops below a number you set, and one when you're out. If you log in already low you get a single reminder. After that it only speaks up when something actually changes.

Rather have it on your action bars? It can make `SC Eat`, `SC Drink` and `SC Eat+Drink` macros that always point at the right item. There are key bindings too, for eating, drinking, or both at once.

No mana, no drink button.

## Installing

1. Grab the latest zip from [Releases](../../releases).
2. Unzip it into `Interface\AddOns` in your WoW Forever folder. During the beta that's `World of Warcraft\_classic_beta_\Interface\AddOns`.
3. The folder has to be called `SnackCheck`. If you used **Code → Download ZIP** instead of a release, GitHub calls it `SnackCheck-main` and the game won't load it until you rename it.
4. Restart the game. `/reload` doesn't pick up new addons.

## Using it

Click to eat or drink. Shift-drag to move the buttons around. Hover to open the list.

## Settings

`/snack` opens the settings (`/food` works too). They're also under Options → AddOns → Snack Check.

| Warnings | |
|---|---|
| Food / Drink | Warn me below this many. 0 turns the low warning off, running out always warns. |
| Show in chat / Show on screen | Where the warnings go. |
| Remind at login | The one reminder when you log in low. It only goes to chat, unless you've turned chat warnings off. |

| Buttons | |
|---|---|
| Match action bar | Copies the size and spacing of your main bar. On by default. |
| Button size / Spacing | Your own size, once you untick Match action bar. |
| Stack vertically | Drink under eat instead of next to it. |
| Count size | The number in the corner. |
| Show buttons | Hide them. Handy if you only use the macros. |

The arrows next to the number boxes do 1 per click, 5 with shift, or just hold them down.

Setting a key binding is click, press a key, done. Right-click clears it. They also show up in the normal keybindings menu under AddOns.

For the macros, tick Make macros, then hit Eat, Drink or Both to put one on your cursor and drop it on a bar. Unticking deletes them again. They take up three of your character macro slots.

Lost your buttons somewhere? `/snack reset` puts them back in the middle of the screen.

## Good to know

Nothing updates during combat, WoW doesn't let addons touch these buttons mid-fight. It catches up as soon as you're out.

Works on non-English clients too.

Settings and bindings are shared between your characters. Pins and macros aren't.

## License

GPL-3.0, see [LICENSE](LICENSE). Versions up to 0.2.1 were MIT.
