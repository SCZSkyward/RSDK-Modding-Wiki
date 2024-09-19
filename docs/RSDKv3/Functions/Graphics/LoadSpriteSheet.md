# LoadSpriteSheet

## Description
Loads a spritesheet and assigns the ID to `Object.SpriteSheet`. The spritesheet must be a GIF file.

!!! note
    Sonic CD Lite can also load PVR files with this function.

## Parameters
- `Path`
The file path to load the sprite sheet from, relative to `Data/Sprites/`.

## Return Value
None.

## Syntax
```
LoadSpriteSheet(string Path)
```

## Example
```
LoadSpriteSheet("Test/Objects.gif")
```