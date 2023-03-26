# Firefox Sidebery

## Features:
  - Edge-like vertical tab design
  - Tree style tab layout support (works with Sideberry & TST (legacy) version)
  - Dynamic Indentation
  - Automatic theme configuration for light and dark themes
  - Custom theme configuration using Sideberry
  - Support for tab groups
  - Support for Tab Containers with visual identification
  - Pinned tabs (right click to close)
  - Built in CSS Extension Management

# How to use

To use FirefoxSidebery you will need to clone this repo into your firefox profile as the `chrome` folder and then follow the Sideberry section below. Both are outlined below in how to do so.

## 1. userChrome.css

Follow the instructions for adding this repository to your Firefox Profile.

1. Navigate to `about:profiles` in your address bar
2. Click on the 'open root folder` button for your current profile
3. Open this folder in your terminal
4. Clone this repo with the following command: `git clone https://github.com/drannex42/FirefoxSidebery.git "chrome"`
5. In Firefox navigate to `about:config` in your address bar
6. change the characteristic `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
7. Restart Firefox

You could skip the clone step entirely if you manually add the FirefoxSidebery files to the "chrome" folder in your Firefox Profile (you will need to make a `chrome` folder if it doesn't exist!).

Visit [userchrome.org](https://www.userchrome.org/how-create-userchrome-css.html) if you are confused or have any questions.

## 2. Sidebery

Load the `sidebery-data.json` file into your Sideberry addon by using the 'import' section under 'Help'.

If you dislike any of the theme presets for dark or light themes, or you have a particular color scheme in mind then navigate to Sideberry Settings > Style Editor (found at the end of the settings sidebar). The preference is to replace the values in the right panel, not in the theme editor to the left - this way you can easily update to newer versions in the future. Paste there the code from `sidebery.css` if you want to use the **Gruvbox Material** theme.

## TreeStyleTabs (Legacy)

Either add the firefox/treestyletabs.css to your TST addon preferences or import the treestyletabs-\*.json preferences to your TST addon (_prefered_)

## Credits

- __[drannex42]__ — for his [FirefoxSidebar](https://github.com/drannex42/FirefoxSidebar)
- __[mgastonportillo]__ — for his [gale for Firefox](https://github.com/mgastonportillo/gale-for-ff)
