## RG Cube [XX] GMU Music Player Config

### Why

- Default `GMU Music Player` on `MuOS` doesn't fill the `720x720 screen`
- The `font` is too `small` for a `boomer`
- The `key bindings` are not `intuitive`

### How

1. Download config files

- [gmu.conf](./gmu.conf) (sets gmu main config to use the next two)
- [rgcube_input.conf](./rgcube_input.conf) (fixed button names)
- [rgcube.keymap](./rgcube.keymap) (intuitive key bindings)

2. Edit default folder location (in `gmu.conf`)

```
Gmu.DefaultFileBrowserPath=<YOUR_FOLDER>
```

3. Copy the files to `/mnt/mmc/MUOS/application/GMU Music Player`

### Keys

```
# Folder View
B = Enter Dir/Add file
A = Add Dir

# Songs View
Start = Change View
B = Play
A = Change Play Mode
X = Clear List
L1 = Prev Song
R1 = Next Song

# Global
L2/R2 + Start = Save & Exit
L2/R2 + B = Help
```
