# Obsidian Theme - Mado Miniflow
Mado Miniflow is a minimalism Obsidian theme, derived from the theme [Mado-11](https://github.com/hydescarf/Obsidian-Theme-Mado-11) and is inspired by the app design of [Doctave](https://www.doctave.com/).
The wave design in the background is made with https://www.shapedivider.app/

This theme aims for a very simplified and clean workflow, unlike how spacious with Mado 11 is, Mado Miniflow lets you focus easily at the center of the screen.

![](img/light-theme.png)
![](img/dark-theme.png)

Recommended fonts for this theme:
- Text: Segoe UI, Noto Sans
- Code: Fira Code

## Mado CSS Classes For Fun!

**Mado-Heading**, for an alternative bulky button feel!

![](img/mado-heading.png)

**Mado-Table**, fancy spacious table with few options such as header-positions `top, bottom, left, right, topless`, styling `stripe, border`, without the fancy style `normal`, and auto-widen `auto`.

![](img/mado-table.png)

**Mado-Panel**, turn all of you lists into panels. Options come with collapsible `list`, panel fixed-sizing `small, medium, large, long, short` with auto-resize `auto`.
  
Callout version comes with `task` option.
  
![](img/mado-panel.png)

**Mado-Explorer**, turn your note into pseudo-File Explorer.

**Mado-Timeline**, centering all elements with minor special adjustment.

**Mado-Daily**, manually stamp your daily card for continuous-streak bonus at every 2nd and 5th day!

![](img/mado-timeline-explorer-daily.png)

## Changelog  

v1.0.0
- Refactored code to be less hacky and adapting Obsidian v1.0 new design.
- More user-friendly easy-to-click buttons that lie at the edges of the screen. 
- Implemented support for Style Settings plugin.
- Introduced more built-in cssclass for fun.
  - cssclass `mado-header` has renamed to `mado-heading` for consistency.

v0.2.3
- Adjusted indent spacing for plain text, code block and quote.

v0.2.2
- Fixed footnote-jumping issue.
   - The wave-design has now moved to `body:before` as it's the reason that causing the issue.

v0.2.1
- Fixed the remaining issue for mobile styling.
- Bullet point restyled to match the position with the text.
- Removed default background color when selected file is unfocused.
- Lines in Graph View are now more visible.
- Adjusted colours for Italic and Bold

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