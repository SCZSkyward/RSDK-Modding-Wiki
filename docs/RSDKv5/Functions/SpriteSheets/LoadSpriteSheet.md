# LoadSpriteSheet

## Description
Loads a spritesheet and returns the ID of it.

## Parameters
- `path`
The file path to load the spritesheet from, relative to `Data/Sprites/`. Spritesheets may **ONLY** be in GIF format.
- `scope`
The asset's scope, may be `SCOPE_GLOBAL` or `SCOPE_STAGE`.

## Return Value
Returns the ID of the loaded spritesheet as a `uint16`. The return value will be `-1` if the animation file failed to load.

## Syntax
=== "C"

	```c
	RSDK.LoadSpriteSheet(const char* path, Scopes scope);
	```

=== "C++"

	```cpp
	SpriteSheet.Load(const char* path, Scopes scope);
	```

## Example
=== "C"

	```c
	MyObject->mySheet = RSDK.LoadSpriteSheet("Test/Objects.gif", SCOPE_STAGE);
	```

=== "C++"

	```cpp
	sVars->mySheet.Load("Test/Objects.gif", SCOPE_STAGE);
	```