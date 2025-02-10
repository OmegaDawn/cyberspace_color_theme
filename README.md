# cyberspace_color_theme
A dark gray and cyan Theme with neon accent colors.

---

<img src="assets/Theme_demo_1.png" alt="Theme demo 1" style="border-radius: 10px; box-shadow: 0 0 8px rgba(128, 128, 128, 0.8);">
<img src="assets/Theme_demo_2.png" alt="Theme demo 2" style="border-radius: 10px; box-shadow: 0 0 8px rgba(128, 128, 128, 0.8);">
<img src="assets/Theme_demo_3.png" alt="Theme demo 3" style="border-radius: 10px; box-shadow: 0 0 8px rgba(128, 128, 128, 0.8);">

## Install
**1.** Open the *Extensions* Tab in *Visual Studio Code* or go to the [*VS Marketplace*](https://marketplace.visualstudio.com/items?itemName=OmegaDawn.cyberspace) <br>
**2.** Search for `Cyberspace` <br>
**3.** Install the Theme <br>
**4.** Select the Theme in the Color Theme menu with `Ctrl + K` `Ctrl + T`


## Tweaks
For a better immersion into the '*cyberspace*' the following extensions can be tweaked to fit the Theme.
These tweaks should be added to the user settings file. *(Open this file by pressing  `Ctrl + Shift + P` search for '`Open User Settings (JSON)`')*

| Extension | Tweak |
| - | - |
[indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) |  <pre>"indentRainbow.indicatorStyle": "light",<br>"indentRainbow.errorColor": "rgba(240,48,80,0.5)",<br>"indentRainbow.colors": [<br>    "rgba(243,18,153,0.7)",<br>    "rgba(207,85,255,0.7)",<br>    "rgba(61,113,255,0.7)",<br>    "rgba(18,186,253,0.7)",<br>    "rgba(6,238,222,0.7)",<br>    "rgba(6,221,139,0.7)",<br>]</pre> |
| [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) | <pre>"todo-tree.highlights.defaultHighlight": {<br>    "background": "#000000",<br>    "foreground": "#00ffbf",<br>}</pre> |
| [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) | <pre>"errorLens.hintGutterIconColor": "#43d6ff",<br>"errorLens.infoGutterIconColor": "#43d6ff"</pre> |
| [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) | Changes in *'Extension Settings'*<ul><li>**Gutter Icon Border Color:** `#00ddff`</li><li>**Gutter Icon Fill Color:**`#00ddff`</li></ul>
|  [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) | *Tweaked colors already included in Theme*

<br>
<br>

| Other settings | Tweak |
| - | - |
| `editor.rulers` <br>*(Python)* | <pre>"[python]": {<br>    "editor.rulers": [<br>        {<br>            "column": 72,<br>            "color": "#50505030"<br>        },<br>        {<br>            "column": 79,<br>            "color": "#505050fe"<br>        }<br>    ]<br>}</pre> |

---
---

## Repository
https://github.com/OmegaDawn/cyberspace_color_theme

## Credits
The showcased languages files: \
    https://github.com/OmegaDawn/syntax_highlighting_demo_files

The theme is based on these color pallets: \
    https://coolors.co/palette/ef476f-ffd166-06d6a0-118ab2-073b4c \
    https://coolors.co/palette/f72585-7209b7-3a0ca3-4361ee-4cc9f0 \
    https://coolors.co/palette/9b5de5-f15bb5-fee440-00bbf9-00f5d4
