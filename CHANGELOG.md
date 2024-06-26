﻿## 1.0.5

- Fixed issue where dragging past a tab row would register the drag as always succeeding, 
even when outside the allowed drag area.
- Fixed issue where the SceneView wouldn't accept drag events

## 1.0.4

- Can now drag assets into a folder tab to move it
- Can now drag scene objects into a folder tab to create a new prefab
- Added menu option `Delete` to delete an asset, while in a folder tab
  - Added hotkey: `Delete` or `X`
- Added menu option `Duplicate` to duplicate an asset, while in a folder tab
  - Added hotkey: `Ctrl+D`

## 1.0.3

- Added a `Open as Floating` context option to menus.
  - Allows you to "pop out " the window instead of having it always dock first
  - Using this instead of the `Properties` option will let you get a floating folder tab

## 1.0.2

- Tweaked more styling so asset labels have a nicer blue highlight

## 1.0.1

- Tweaked padding with list view in folder tab
- Added selection text & icon in footer of folder tab
- Added `Reset Zoom` right-click option to zoom slider
- Added documentationUrl to package.json
- Fixed list view background coloring

## 1.0.0

- Initial version