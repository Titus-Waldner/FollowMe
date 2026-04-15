![Logo](img/ogFollowMe.png)
# Follow Me

**Fork Notice**  
This is a **community fork** of the original **Follow Me** module by **oOve** (Dr.O).  
All credit for the original idea and code goes to the original author.  
**This fork has been updated for Foundry VTT V11 compatibility** (no more console warnings, updated collision handling).

**Follow Me** is a module for [Foundry VTT](https://foundryvtt.com/ "Foundry VTT") that allows tokens to follow or be followed by other tokens. This is completely system agnostic, and fully customizable to fit right into your game.

<p align="center">
![GitHub release (latest by date)](https://img.shields.io/github/v/release/oOve/followme?style=flat-square)
[![Become a Patron](https://img.shields.io/badge/support-patreon-orange.svg?style=flat-square&logo=patreon)](https://www.patreon.com/drO_o)
</p>

# Usage
Select your token, hover the mouse over the one you wish to follow and press the "**f**" key. Your token now follows behind maintaining the same distance. To stop following, simply move your token.

![ezgif-3-5912d53231](https://user-images.githubusercontent.com/8543541/167747299-fa7949a4-64b7-4106-b378-a1dd4a253922.gif)

The scrolling text above the token on follow and "unfollow" is enabled/disabled by the "core setting" called "Scrolling Status Text".

# Installation
It's always better and easier to install modules through the in-app browser. Just search for "Follow Me"

To install this module manually:
1. Inside the Foundry "Configuration and Setup" screen, click "Add-on Modules"
2. Click "Install Module"
3. In the "Manifest URL" field, paste the following url:  
   `https://github.com/Titus-Waldner/FollowMe/releases/latest/download/module.json`  
   *(or your own fork's manifest URL)*
4. Click 'Install' and wait for installation to complete
5. Don't forget to enable the module in game using the "Manage Module" button

# Localization
Current support for:
 * English -- https://github.com/oOve
 * German -- VTTOM, Lucky13524
 * Your language ?

If you want to translate this module, download [this file](lang/en.json) and translate it. After that open an issue sharing your translation. Also share the default name convention for your language. You can find that by either, finding a system or module that is already translated to your language and open its module.json. It should look something like this:  
```json
"languages": [ { "lang": "en", "name": "English", "path": "lang/en.json" } ]