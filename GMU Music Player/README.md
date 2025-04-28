## RG Cube [XX] GMU Music Player Config

### Why

- Default `GMU Music Player` on `MuOS` doesn't fill the `720x720 screen`
- The `font` is too `small` for a `boomer`
- The `key bindings` are not `intuitive`

### How

1. Download config files

- [anbernic.keymap](./anbernic.keymap)
- [gmu.conf](./gmu.conf)

2. Edit default folder location (in `gmu.conf`)

```
Gmu.DefaultFileBrowserPath=<YOUR_FOLDER>
```

3. Overwrite files in `/mnt/mmc/MUOS/application/GMU Music Player`

### Keys

```
L1 = Prev Song
R1 = Next Song
Start = Change View
L2/R2 = Mod
Mod+Start = Exit
A = Change Play Mode
B = Play/Pause
Y = Remove Item
```
