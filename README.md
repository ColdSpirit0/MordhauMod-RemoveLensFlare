# Remove Lens Flare

Removes lens flare effect when map starting


## How to install
1. Create the directory `.../MORDHAUEditor/Mordhau/Mods/RemoveLensFlare`.
2. Move to the directory and open the command prompt.
3. Write `git clone https://github.com/ColdSpirit0/MordhauMod-RemoveLensFlare.git .`


## Config example

```ini
[/Script/Mordhau.MordhauGameSession]
Mods=3758915 ; https://mod.io/g/mordhau/m/remove-lens-flare

[/Script/Mordhau.MordhauGameMode]
SpawnServerActorsOnMapLoad=/RemoveLensFlare/BP_RemoveLensFlareInit.BP_RemoveLensFlareInit_C
```