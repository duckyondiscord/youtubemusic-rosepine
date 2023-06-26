<h3 align="center">
	RoséPine for <a href="https://music.youtube.com">Youtube Music</a>
</h3>

## Usage
### [Youtube Music Desktop App (th-ch)](https://github.com/th-ch/youtube-music)

1. Create a new css file with the contents in src/rosepine.css and optionally paste in the code below too.
2. Assuming you have the latest build with the theme selection menu, open the app, click `Options > Visual Tweaks > Theme > Import custom CSS file`, and choose the CSS file.

### [Youtube Music Desktop App (ytmdesktop)](https://github.com/ytmdesktop/ytmdesktop)

1. Navigate to the settings of the Youtube Music Desktop App.
2. Go to the appearances tab and turn on custom theme.
3. Click on the pencil icon to open up the editor window.
4. Paste in src/rosepine.css and optionally the code below.

### The code


```css
/* if you want to change the accent color, paste this in aswell and change the hex code - or use one of the predefined colors with var(--ctp-'color') - e.g. var(--ctp-maroon) */
html:not(.style-scope) {
    --ctp-accent: #eb6f92 !important;
}
```


## 💝 Thanks to
Catppuccin team for the base CSS file.

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
  <br>
  Copyright &copy; 2023-present <a href="https://github.com/duckyondiscord" target="_blank">ducky</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
