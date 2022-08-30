Changes on this fork:
- Bottom status bar hidden
- Vault name hidden
- Side panels completely hidden (I activate via shortcut when I need them, also accessible via command pallet).







`ln -s theme.css /Users/aidangibson/Library/Mobile\ Documents/iCloud~md~obsidian/Documents/Ext\ Brain/.obsidian/themes/80sNeonFork.css`

symlinked from here to there



NOPE dont symlink it made all themes in folder not work (known issue, Obsidian actually doesn't support symlinks. maybe try hard link??)



# todo

- [ ] refactor all of it using obsidian 16 guidelines [0.16.0 Theme Migration Guide - Announcements - Obsidian Forum](https://forum.obsidian.md/t/0-16-0-theme-migration-guide/42537)
  - [ ] change structure of plugin to follow v16 guidelines, have the two separate versions for prev16 and postv16, etc, p much prep for store
  - [ ] go deep in v16, see what it enables
- [ ] get rid of cmd+L and cmd+R toggle so they are never visible
- [ ] compare with default light theme, compare with v15.9 version, etc.

i probably shouldn't directly implement pane relief css hotfix, I'll leave that as a snippet for now. 

- [ ] save my CSS snippets in github
- [ ] have a better overall setup so I'm not manually copying css files for my vault <-> this repo
- [ ] code within highlight is illegible color. like ==`test`==



# 80s Neon for Obsidian.md

A retro-future 80s inspired theme for [Obsidian](https://obsidian.md/), compatible with Obsidian V0.5.0
![Screenshot](./screenshot.jpg)

## Install
1. Download obsidian.css to your Obsidian vault folder.
2. In Obsidian, click Settings->Plugins and turn on "Custom CSS".
3. There is no step 3! Enjoy!

## Bonus! CRT scanlines and flicker!
There's a bonus animation, commented out by default in the CSS file.  
Uncomment it and you get an old-school CRT effect with a chunky pixel pentile look,
flickering screen and blurring text. All credit to [Alec Lownes](http://aleclownes.com/2017/02/01/crt-display.html)
![Animation](./animation.gif)

## License
I don't really care what happens to this theme, so I put it under [The Unlicense](./LICENSE) and set it free!
