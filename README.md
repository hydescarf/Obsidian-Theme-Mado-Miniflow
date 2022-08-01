# Obsidian Theme - Mado Miniflow
This is a minimal theme version derived from the theme [Mado-11](https://github.com/hydescarf/Obsidian-Theme-Mado-11) and is inspired by the app design of [Doctave](https://www.doctave.com/). Certain styles are added, tweaked and removed from the original theme.
The wave design is made with https://www.shapedivider.app/

The special CSS class `mado-side-button` is removed on this version, however, `mado-header` is remained.

This theme is intended for minimal workflow like what you're looking at currently, and may not support other types of plugin and workflow.

![](cover-light.png)
![](cover-dark.png)

## Index

- [Installation](#installation)
- [Guideline](#guideline)
- [Changelog](#changelog)


## Installation

- Download the file "obsidian.css" and place it inside your Obsidian Snippet Folder. (You may rename the file to your liking)
- Enable it through Settings → Appearance → CSS Snippets.

Or

- ~~Download the theme through Obsidian's theme store!~~ (Not ready yet)


## Guideline

### Where are all the buttons?
Similar to Mado-11, buttons are all hidden by default, and can be hovered to reveal them. However, the hovering is much easier to be triggered here.

#### Top Menu

- Back & Forward buttons - hidden, hover to show. Position is at the top-left corner.
- Min/Max/Close buttons - hidden, hover to show. Position is at the top-right corner.
- App Title and Vault Title - hidden.

#### Left Sidebar

- New Note/New Folder/Rearrange buttons - hidden, hover to show. Position is at the top-right corner of the left-sidebar.
- Ribbon buttons (Settings, Change Vault, etc.) - hidden, hover to show. Position is at the bottom-left corner.

#### Sidebar

- Dock-Collapse buttons - hidden, hover to show. Position is around the top-left/right corner.
- Tab Menu on the dock - hidden, hover to show. Position is around the top-edge of the dock inner border.

#### Other

- Recommended Font: Segoe UI, Noto Sans JP
- Resize Handle - hidden, hover to show.
- Status Bar - hidden.



### Adjustable CSS Elements
There are a few adjustable elements in the file where user can directly adjust them.
They can be found by searching for the keyword "`/* ADJUSTABLE CSS */`" in the file.
- "Navigation Folder Title" or "Vault Title" on the left can be toggled on and off by `display:none`.
- The **Left** Side Panel has a shorter `padding-top` compared to the right.
- The Wave design at the bottom can be disabled.
	- Also, due to the introduction of the Wave design, the side panels `background` is now `none`, to let the design to be seen through.
	- Which, may in turns **tune down the readibility during translucent mode**.
- Finally, the `max-width` of the notes is now fixed at `830px`.

## Changelog  

v0.1.0
- Release!