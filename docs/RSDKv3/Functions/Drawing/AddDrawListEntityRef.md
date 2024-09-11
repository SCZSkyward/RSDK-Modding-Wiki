# AddDrawListEntityRef

## Description
Adds `ObjectPos` to the drawList layer.

## Parameters
- `Layer`
Layer of the drawList to add the reference, indices 0-7 are valid, additionally 8 is available in V5U.
- `ObjectPos`
The position of the object to add.

## Return Value
None.

## Syntax
```
AddDrawListEntityRef(int Layer, int ObjectPos)
```

## Examples
```
AddDrawListEntityRef(4, Object.EntityNo)
```