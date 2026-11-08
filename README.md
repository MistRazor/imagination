# Imagination

![MistRazor presents Imagination Mod](https://cdn.modrinth.com/data/cached_images/f92443f5c2f20ab0750662cf3ab669434fd00bc8.png)

Imagination gives you a creative-like planning layer inside your survival world. Imagine a build exactly where it will stand, then build it for real over a see-through blueprint. You never leave your world, and you never need to fuss with schematics.

---

## Why Imagination?

Here's how players usually plan a big survival build:

1. Leave the survival world.
2. Open a creative world and build the design there.
3. Export it as a schematic.
4. Go back to survival, load the schematic, and nudge it into position.
5. To build with friends, send everyone the file and make sure they all place it at exactly the same coordinates.

With Imagination it's one step: **press I and start building.** The plan goes exactly where it belongs, in the world you're already playing. Your friends can see it too, already placed perfectly, with no files to send and no schematic placements to coordinate.

---

## How it works

**1. Imagine.** Press **I**. Your character stays put while a projection of your consciousness lifts away in flight with a creative inventory of every block in the game.

**2. Design.** Build, dig, pour water and change your mind as often as you like. Nothing you do changes the real world, and nothing you place costs a thing.

**3. Come back.** Press **I** again to return to your body, with your survival inventory exactly as it was. Your design is still there, as translucent imaginary blocks floating in the world.

**4. Build it for real.** Place real blocks over the imaginary ones. Each imaginary block disappears as soon as a real block matches it, so whatever is left shows the work still to do.

---

## Build together, or in secret

On a server running Imagination, everyone plans on the **same imaginary layer**. A friend lays out the walls while you work on the roof, and you see each other's changes as they happen. Imagining players see each other as translucent figures, so you know who's working on what.

Want to keep a surprise build secret? **Hold sneak as you press I** and you'll enter a **private layer** that nobody else can see. When it's ready for its reveal, share part or all of it onto the shared layer. Or use it straight from the private layer if you're building by yourself.

Press **R** to choose which layers you see: shared, private, both, or neither.

LAN worlds share too, once you open them to LAN.

And even on a purely vanilla server, client-side Imagination still works for solo builds! (You just won't be able to use the shared layer.)

---

## Reading the blueprint

Outside Imagination, translucent imaginary blocks tell you what's left to do:

| Highlight | Meaning |
|---|---|
| **No Highlight** | Nothing built here yet |
| **Red** | The wrong block, or you planned to have an air gap here |
| **Orange** | The right block, but facing or shaped wrong |
| **Green** | A block your imaginary water or lava would create |

You can decide how strictly a real block has to match before its imaginary version vanishes: the exact block, the same material (any wood for wood), similar properties, or anything with the right shape.

When imaginary blocks get in the way while you're climbing around, **Safe Footing** fades the ones near you so you can always see the real ground.

---

## Tools for bigger plans

Imagination has its own tools hotbar, only visible while imagining:

- **Box Select** and **Magic Wand Select**: pick out part of a build, then move, copy, rotate, flip, fill or delete it.
- **Imaginary Pickaxe**: breaks imaginary blocks, or imaginary air, and leaves the real world alone.
- **Imaginary Pencil**: draw reality back over your imaginary blocks, or erase them into imaginary air.
- **Imaginary Water and Lava Buckets**: flood a connected space up to a chosen height, one click per chunk.

**Undo and Redo** with Ctrl + Z and Ctrl + Y.

---

## Plan with water and lava

Imaginary water and lava flow by the game's real rules, at normal speed, 5x speed, or turn off the flow entirely. Test a waterfall, a moat, a mob farm's water stream or a lava blade before you spend a single bucket. Imaginary fluids meet real ones properly, and they make cobblestone, obsidian or basalt where real fluids would. And those generated blocks (highlighted green) don't need to be manually removed if you restructure your build; they'll disappear automatically if the current configuration would no longer generate them.

And cleaning up existing water and lava is a snap! You can select water and lava with the magic wand select or box select tools and delete them just like that.

You can also use **imaginary air** to picture real blocks gone: a hillside cut away, a basement dug out, a cave widened. All of it happens before you even break ground in the real world.

---

## From plan to finished build

- **Import schematics.** Already have designs as `.litematic`, `.schem` or `.nbt` files? Bring them into Imagination and place them wherever you like.
- **Materials list.** Select a plan and export everything it still needs, item by item, with stack counts, in Litematica's materials list format, so it works with other mods that read Litematica material lists.
- **Easy Place.** Right-click a ghost block to place the matching real block from your inventory, already facing the right way. (Disabled by default.)

---

## Safe while you daydream

Your body stays behind while you imagine, but you're never left defenseless. If something hurts your body or knocks it around, you're snapped straight back with a red flash and an attention-grabbing sound. Both can be turned off.

A soft cross-dissolve and a harp flourish mark the trip in and out. You can adjust or switch off both.

---

## Fair play, built in

Imagination is designed so it can't give anyone an unfair edge:

- Your private imaginary blocks and creative inventory exist **only on your computer**. The server never receives them, and they never turn into real blocks or items.
- Your character **doesn't move or act** while you imagine.
- On servers that haven't enabled noclip, the camera **stops at real blocks** instead of passing through them.
- Removing blocks in your imagination **never reveals what's hidden behind them in reality**. Caves, ores and secret rooms you couldn't already see show up as plain placeholder blocks, even on the F3 screen. But if this seems like overkill, server admins can turn it off.

That's why it works on **vanilla servers** as well. There, your plans simply stay private, and block revealing and noclip are disabled.

---

## For server owners

Install Imagination on your server to unlock shared planning and set the rules. It adds no new blocks or items, so players without the mod can still join as usual.

For each of these abilities, you choose who gets it: **everyone, ops only, an allowlist, or nobody**.
- Reveal real blocks by imaginary digging
- Fly through real blocks while imagining
- Import schematics onto the shared layer
- Easy Place

On a dedicated server, seeing behind imaginary air and flying through blocks both start switched off for everyone.

You can also turn shared imagination off entirely. And you can stop players from overwriting shared blocks when they share their private plans.

Ops change all of this from the in-game settings screen, and changes take effect immediately, no relog or restart necessary. If you prefer, edit `config/imagination-server.json` instead. (Note: Editing the JSON file directly **does** require a server restart to reflect in-game.)

---

## Controls

| Key | What it does |
|---|---|
| **I** | Start or stop imagining (**hold sneak** for a private session) |
| **R** | Choose which layers you see; while imagining, switch between shared and private |
| **O** | Share, import schematics, export a materials list |
| **0** | Imaginary tools slot |
| **Left Alt** | Tools menu and extra hotbars |
| **Left Ctrl** | Modify a selection; **with Z** to undo / **with Y** to redo |
| **Enter** | Perform a selection fill |
| **Delete** | Delete the selected blocks |

Settings, Safe Footing and Easy Place can each be given a key too. Everything can be rebound under **Controls → Imagination**.

---

## Installing

| | Fabric | NeoForge |
|---|---|---|
| **Needs** | Fabric Loader, Fabric API | NeoForge |
| **Optional** | Mod Menu, for a settings button | n/a |

Put Imagination on your **client** to use it anywhere. Add it to the **server** as well for shared imagination and server rules.

Your imaginary blocks are saved separately for each world and server: private plans on your computer, shared plans on the server. Schematics to import go in `.minecraft/schematics`.

---

*Imagination is in beta. If something looks wrong, please report it on the issue tracker.*
