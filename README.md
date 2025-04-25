# Deezer-Toggle-Features
Userscript to toggle custom features in Deezer and some other things. Install with a userscript manager like Violentmonkey.

[GreazyFork](https://greasyfork.org/en/scripts/533942-toggle-features)
[GitHub](https://github.com/bertigert/Deezer-Toggle-Features)


## Usage
Open the [toggle_features.js](https://github.com/bertigert/Deezer-Toggle-Features/blob/main/toggle_features.js) file and take a look into the Settings Section. (Edit it in your userscript manager)

```js
// ======= Settings START =======  
const LOG_ALL_FEATURES_DEBUG = true; // useful to see all features (gets logged in the (dev tools) console, use https://github.com/bertigert/DeezMod/blob/main/plugins/enable_dev_mode.js to view)

const DEEZER_CUSTOM_FEATURES = {
    // gapless_playback: true,
    deeztools: true, // simple way to toggle most of the custom features
}

SPECIAL_FEATURES = {
    spoof_family: true, // Spoof your account to be the head of a family plan, opening up more features for you. (e.g. linking to last.fm)
}

// ======= Settings END =======
```
Set values to true to enable them and to false to disable them.
