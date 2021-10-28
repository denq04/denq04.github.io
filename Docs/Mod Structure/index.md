---
order: 10
---

# Mod Structure

These are the definitions of what the structure of the mod looks like.

Mod's files can be in folder or in zip archive. Usually archive should be with `*.mod` extension.
Structures inside folder or archive are the same.

### Structure

- Mod's root folder/archive
    1. [`/Code`](./code-folder.md) folder
        - `*.cs` files
    2. [`/EmbededResources`](./embedresources-folder.md) folder
        - Any files that you want to use as embeded resources in your mod
    3. [`icon.png`](./icon.png.md) mod's icon
    4. [`mod.json`](./mod.json.md) definition of the mod
    5. Any other files and folders that you want to use in your mod

[1]: code-folder.md
[2]: embedresources-folder.md
[3]: icon.png.md
[4]: mod.json.md

### Example

```json
{
    "name": "Example mod",
    "author": "Nikon#7777",
    "version": "0.0.1",
    "description": "This is an example mod's description!",
    "iconPath": "icon.png"
}
```