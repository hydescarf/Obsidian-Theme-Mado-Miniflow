# Obsidian Theme - Mado Miniflow
This is a minimal theme version derived from the theme [Mado-11](https://github.com/hydescarf/Obsidian-Theme-Mado-11) and is inspired by the app design of [Doctave](https://www.doctave.com/). Certain styles are added, tweaked and removed from the original theme.
The wave design is made with https://www.shapedivider.app/

The special CSS class `mado-side-button` is removed on this version, however, `mado-header` is remained.

This theme is intended for minimal workflow like what you're looking at currently, and may not support other types of plugin and workflow. However, feel free to pull a request for plugin supports, they may be in lower priorities but I'll take my time to support them

![](cover-light.png)
![](cover-dark.png)

## Index

- [Guideline](#guideline)
- [Changelog](#changelog)



## Guideline

### Where are all the buttons?
Similar to Mado-11, buttons are all hidden by default, and can be hovered to reveal them at their default position. However, the hovering is much easier to be triggered here.


### Other

- Recommended Font: Segoe UI, Noto Sans JP
- Resize Handle - hidden, hover to reveal.
- Status Bar, App Title, Vault Title - hidden.



### Adjustable CSS Elements
There are a few adjustable elements in the file where user can directly adjust them.
They can be found by searching for the keyword "`/* ADJUSTABLE CSS */`" in the file.
- "Navigation Folder Title" or "Vault Title" on the left can be toggled on and off by `display:none`.
- The Wave design at the bottom can be disabled.
- Finally, the `max-width` of the notes is now fixed at `830px`.

## Changelog  

v0.2.0
- Dock ribbon buttons are restyled for easier hovering.
- Workspace tabs, as well as sidebar vertical spacing are readjusted.
- "File Explorer" buttons are restyled and reverted back to their original position.
- Drag-Handler position are adjusted, you can now easily find their position by hovering just at the edges of the main/middle pane.
- Highlighted text in dark mode from the search result is now more readable.
- Background issue in Translucent Mode is now fixed.

- Mobile fixes:
   - Note title and buttons are adjusted.
   - Side margins beside the main note are removed.
   - Setting menu size is adjusted.
   - Ribbon buttons are no longer hidden by default.
   - Fixed weird bottom margin on the whole screen.
   - Applied padding in the main note.

v0.1.0
- Release!