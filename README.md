<!--
  Author:  happx https://github.com/happ-2h
  Date:    2022 December 01
  Purpose: FL Studio dynamic wallpaper README

  Version: 1.0.0
-->

<p align="center"> 
  Dynamic wallpapers for FL Studio.
</p>

> If you know you have a low-spec computer, consider [Editing Files](#editing-files) before loading them.

> Any media shown in the examples will not be distributed/included in case of any copyright infringement.

## Table of Contents

- [Getting Started](#getting-started)
- [Editing Files](#editing-files)
- [Getting Help](#getting-help)
- [FAQ](#faq)

## Getting Started

### Downloading
- Download individual wallpapers: `right-click (index.html) > Save link as...`
  - I recommend putting them in individual folders, especially if they require images, else rename them if you plan on downloading more, or just to distinguish them.
  - If you want to download one pack, this is the way to do it.
- Download all packs: on the [main repository link](), click the <kbd>Code</kbd> button > **Download ZIP**.
- You can also `git clone` if you use Git.

### Save Path
- You can save it anywhere FL Studio is allowed to access, but it's recommended to save them in `..\FL Studio 20\Artwork\Wallpapers\`

### Apply
- You can apply the new wallpaper via FL Studio: `VIEW > Background > Set dynamic wallpaper / HTML document...`

### Updating
- *Update checking will have to be done manually for now.*
- If you made any personal edits, **back them up**!
- To get *my* updates, redownload the zip or individual file. You can choose to overwrite existing files (this choice will overwrite personal edits, which is why I recommend backing up your work).
- With `git pull`.

## Editing Files

- Forenote: the FL browser uses an embedded Internet Explorer browser, so many new CSS and JS features will not work!
- Open the `index.html` in a plain text editor (code editors with at least syntax highlighting are recommended).
- There are detailed comments (text following `//` or in between `/* */`) on the things you can safely change. You may change other non-commented things, but it may break the wallpaper.
- To see your changes (if the wallpaper is already set), right-click on the wallpaper inside FL Studio, and click `Refresh`.
  - If this doesn't work, you may have to [re-apply](#apply) it.
### Debug
- To debug your work, I recommend using a browser with development tools, as the FL Studio browser does not have any that I know of.

## Getting Help

- You can write to me on [GitHub](https://github.com/happ-2h) or comment on [my YouTube channel](https://www.youtube.com/@officialziran).
- I may not be able to help on heavily modified or 3rd party (redistributed) wallpapers.

## FAQ

- Does the window size impact performance?
  - Yes, the only fix is to work in a smaller window or modify the source code to do less calculations and/or drawings.
- Does having a dynamic wallpaper impact overall performance \[of the computer\]?
  - Yes. If you have a graphics card, most the rendering is done there; however, the CPU still has to do calculations so it's still used.
    - *Currently unknown about the behavior of integrated graphics*.
- Can I redistribute my edits?
  - Yes. I would appreciate *original author* credit as links to either (or both) my [GitHub](https://github.com/happ-2h) or [YouTube](https://www.youtube.com/@officialziran) channel, though it's not necessary.
- Can I show or use them in a video?
  - Yes. I would appreciate credit as links to either (or both) my [GitHub](https://github.com/happ-2h) or [YouTube](https://www.youtube.com/@officialziran) channel, though it's not necessary.
- Why doesn't FL Studio react to keypresses anymore?
  - You'll have to click on an FL Studio GUI element (such as the playlist, mixer, channel rack, etc.) to give key events back to FL Studio.
