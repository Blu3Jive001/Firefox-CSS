# Firefox-CSS

This repository holds my custom css for Firefox and other websites (with the stylus extension). This code is not 100% mine. Some of it came from JavaCafe01 and other bits from MrotherGuy.

My css is messy, if you find a problem and figure out how to improve my code, please do!

## Setup

### Firefox css

1. In the searchbar type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`**, **`layers.acceleration.force-enabled`**, **`gfx.webrender.all`**, and **`svg.context-properties.content.enabled`**. Change them to **True**
3. Go to your Firefox profile:
    - If you're on Linux: `$HOME/.mozilla/firefox/XXXXXXX.default-release/`
    - If you're on Windows: `C:\Users\<USERNAME>\AppData\Roaming\Mozilla\Firefox\Profiles\XXXXXXX.default-XXXXXX`
    - If you're on MacOS: `Users/<USERNAME>/Library/Application Support/Firefox/Profiles/XXXXXXX.default-XXXXXXX` 
4. Create a folder and name it **`chrome`** (with lowercase).
5. You can choose between the three versions: **HideURLBar**, **WithURLBar** and **OneLine** (You can see them here: [Versions](#three-versions)). Once you choose your version  and rename the file you choose into `userChrome.css`.
6. Then paste the `userChrome.css` and the `userContent.css` files into the folder.
7. (Optional) If you don't know if use a theme or not, you can use the Add-on theme I made for a better experience: [Add-on Theme](https://addons.mozilla.org/en-US/firefox/addon/simplerentfox)
8. Enjoy!

You should also set Firefox to "compact" and "dark mode". Those two options are available under menu > customize.

### Stylus

Install the [stylus firefox extension](https://addons.mozilla.org/en-US/firefox/addon/styl-us/).
After that copy & paste the contents of the files in the stylesheets folder over into your extension settings.

## Screenshots

### Browser

![oof](https://github.com/Blu3Jive001/Firefox-CSS/blob/master/screenshots/browser.png)

### Github

![oof1](https://github.com/Blu3Jive001/Firefox-CSS/blob/master/screenshots/Github.png)

### Discord

![oof2](https://github.com/Blu3Jive001/Firefox-CSS/blob/master/screenshots/discord.png)

## Acknowledgments
[firefox-review](https://github.com/fellowish/firefox-review)
