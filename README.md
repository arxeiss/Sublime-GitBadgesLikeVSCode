# git badges like VS Code

This plugin changes default Sublime Text git badges in left sidebar into VS Code looks.
Instead of dots and chevrons there are letters `A`, `M`, `S` and `U`. Also colors are changed.

Based on [OdatNurd's gist](https://gist.github.com/OdatNurd/4bb596e6162693567642b7aef4cab4c0)

## Install

Install as plugin via [Package Control](https://packagecontrol.io/packages/Git%20badges%20like%20VS%20Code)

> Note that this plugin works only on Sublime Text 3.2 and above *(>=3200)*, as in this version native git implementation was added.

### Usage with other than default themes

If you are using another theme like Ayu or others, you cannot switch theme, but only color schema.
Because there is difference between **Select color scheme** and **Select Theme**.

So do the following:

1. Open command pallete (CTRL + Shift + P) and type **UI: Select Theme** and select Adaptive or Default/Default Dark. (**not** Ayu or others)
2. Open command pallete (CTRL + Shift + P) and type **UI: Select Color scheme** and select any of Ayu or others.

## How it looks

![New VC Code like badges](./screenshot.png)

**Explanation:**<br>
- New files are **green** with `U` badge (untracked) or `A` badge when added to staging area
- Modified files are **yellow** with `M` badge when unstaged or `S` badge when staged
- Folder of deleted file has no color (red evoke error) but has **red** circle badge
- Conflicted file is **red** with git merge badge
- Folder has always circle badge (no letter or icon) except Conflicted

## Contribute

Contribution is welcome. Leave an Issue or Pull request

### Icons

Icons must be in PNG format in RGB mode (not palette mode). Use prepared PSD in [Photopea](https://www.photopea.com), which can export file in RGB mode.

## Changelog

### v1.2.0

- Added new Default Dark theme, which was added in ST4
- Improved looks in Default (light) and Adaptive theme

### v1.1.0

- Create new `A`, `M`, `S` and `U` icons
- Fixed path to custom icons

