# Set16x16TileInfo

## Description
Sets the info for `InfoTile` from a tile at `TileX`, `TileY` to the new `value`

## Parameters
- `Value`
The new value for the tile's specified `InfoType`
- `TileX`
Position of the 16x16 tile in the map on the horizontal axis
- `TileY`
Position of the 16x16 tile in the map on the vertical axis
- `InfoType`
The ID for the type of info that will be overwritten from the tile, valid values are: 
    0 - TILEINFO_INDEX
    1 - TILEINFO_DIRECTION
    2 - TILEINFO_VISUALPLANE
    3 - TILEINFO_SOLIDITYA
    4 - TILEINFO_SOLIDITYB
    5 - TILEINFO_FLAGSA
    6 - TILEINFO_ANGLEA
    7 - TILEINFO_FLAGSB
    8 - TILEINFO_ANGLEB
## Return Value
None.

## Syntax
```Set16x16TileInfo(int value, int TileX, int TileY, int InfoType)```

## Examples
- ```Set16x16TileInfo(3, TempValue0, TempValue1, 7)```