# Map Atlases

<a href="https://www.curseforge.com/minecraft/mc-mods/fabric-api"><img src="https://i.imgur.com/Ol1Tcf8.png" width="149" height="50" title="Fabric API" alt="Fabric API"></a>

A vanilla-friendly mini-map/world-view mod using vanilla Maps, introducing the "Atlas".

The "Atlas" features and details:
- Crafted with a **Filled** Map (the source map), a Book, and something sticky (Slimeball or Honey Bottle). The source map determines the Atlas' scale. *Who knew this whole time, all you had to do to get a mini-map was slap a map onto a book?*
- When the Atlas is on your hot-bar or off-hand, it will render your current-position Map on the HUD if a such Map exists inside the Atlas.
- You can put both Filled Maps and Empty Maps with an Atlas in a crafting inventory to insert either Map type into the Atlas.
- Filled Maps which are added **must** be of same Scale.
- There's a maximum of 128 Maps in each Atlas (configurable).
- Filled Maps inside the Atlas will continue updating your location & world-state.
- Empty Maps are consumed when you enter an un-mapped region to generate a new Map of the corresponding Scale.
- You may also **cut out Maps** when putting it in a Crafting Grid with Shears. 
   - This will remove Filled Maps from the Atlas until only the Source Map is left, which cannot be cut out. 
   - It will then start removing Empty Maps from the Atlas if there are no Filled Maps left inside (besides Source Map).
   - This does consume Shear's durability (Unbreaking still functions though).
- The Atlas has a world map view as well. To access this, right-click the Atlas or press "m" while the Atlas is on your hot-bar.
- The Atlas world view has scales by odd numbers and supports 1x1, 3x3, 5x5, 7x7, etc.
- The Atlas world view has full pan support as well, using your mouse to drag the world map.
- Atlases also support right-clicking Banners to add "waypoints", which display in both the mini-map & world-view map.
- Atlases can be duplicated with a Cartography Table - simply put an Atlas in the top & bottom slots and the top Atlas will copy its contents to the bottom Atlas (& override the bottom Atlas).
- You can also add Empty Maps to the Atlas using a Cartography Table as well.
- Atlases have 3 sounds: An opening world-view sound, a new map drawing sound, & a page flipping (new mini-map displaying) sound.
- **Note**: Atlases are limited to the Overworld due to some buggy code out of my control.
- The mod has config control for configuring the maximum number of maps allowed in an Atlas, to force the mini-map or world-map scale on your GUI, to disable Empty Map entry + new-map generation, to disable mini-map drawing entirely if you prefer not to have it, to configure where it activates, & the mini-map anchoring point, x offset, & y offset.

Future ideas:
- Fix issues with Atlases in other dimensions.
- Putting an Atlas in a Lectern.

## Crafting an Atlas
![2022-06-24_19 46 45](https://user-images.githubusercontent.com/17690401/175755582-aecd94b1-ac3a-4686-a3d5-82cea1e3583d.png)
![2022-06-24_19 47 16](https://user-images.githubusercontent.com/17690401/175755583-83e57650-ce2b-49e3-93e6-a0cf67ff1d0d.png)

## Maps inside the Atlas will render if the Atlas is on your hot-bar
![2022-06-24_19 45 51](https://user-images.githubusercontent.com/17690401/175755590-dedbaaf0-f970-4755-a42f-484264609811.png)

## Adding more Maps to an Atlas
![2022-06-24_19 48 05](https://user-images.githubusercontent.com/17690401/175755596-5895ebab-b1a2-4c58-bc70-dcb03083762f.png)

## Current Map is rendered when you move locations
![2022-06-24_19 47 43](https://user-images.githubusercontent.com/17690401/175755619-576688bb-2103-4f52-8b6a-a4264b790e93.png)

## Custom Tooltip
![2022-06-24_19 48 21](https://user-images.githubusercontent.com/17690401/175755670-3819eca7-cbc4-4be5-a7c8-3d4286dacd19.png)

## World Map View
![2022-06-24_19 45 39](https://user-images.githubusercontent.com/17690401/175755623-3583c96f-606d-4bf8-9912-98e567b4fad4.png)

## Cutting a Map out of an Atlas
![2022-06-24_19 48 45](https://user-images.githubusercontent.com/17690401/175755627-bf5ff6b5-752d-4bfd-85d2-82c863bc1257.png)

## Duplicating an Atlas
![2022-06-24_19 46 20](https://user-images.githubusercontent.com/17690401/175755632-2c6d953d-2ce2-4020-b2ff-ee5cd85aa6f6.png)

## Mass adding Empty Maps to Atlas
![2022-06-24_19 46 08](https://user-images.githubusercontent.com/17690401/175755635-751ed66c-11f2-448e-96e4-7cf20d2ddc07.png)

Sound Sources
- [Atlas open sound](https://freesound.org/people/InspectorJ/sounds/416179/)
- [Atlas page flip sound](https://freesound.org/people/flag2/sounds/63318/)
- [Atlas new map creation sound](https://freesound.org/people/Tomoyo%20Ichijouji/sounds/211247/)
