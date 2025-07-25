# ❓ What is this?
Here are tweaks that change the browser UI itself. As such, this is browser specific.  

## ✨ Features

- Floating Sidebar and sidebar tweaks
- Picture-in-Picture tweaks

## 🛠️ Installation

### Method 1: Enable userChrome (manual updates)
This method does not require external tools but requires manual updating. It will also allow you to make your own userChrome changes.
1. In your browser, go to `about:config`
2. Search `toolkit.legacyUserProfileCustomizations.stylesheets` and set to `true`
3. Go to `about:profiles`. Find the profile you want to modify, and click on `Open Folder` of the `Root Directory`
4. Navigate in the `chrome` folder. Create a `userChrome.css` and copy and paste the styles into that file.
5. Restart your browser

### Method 2: Install Sine (automatic updates)
This method requires installation of a 3rd party application but allows the download and management of mods more easily.
1. Go to the repo of [Sine](https://github.com/CosmoCreeper/Sine) and follow the instructions to install Sine
2. `Sine Mods` should be available in the browser's settings page after installing
3. In the `Marketplace` section, there will be a box that allows you to install your own mods by adding a repo link. Paste https://github.com/andyltang/Browser-Tweaks/tree/main/browser and click `Install`  

## 🧩 Compatibility
Tested on Zen Browser. It is also expected to work on most Firefox and forks, but ymmv.  
It is NOT compatible with Chromium based browsers.
