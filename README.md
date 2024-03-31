# AutoFarmCatizen

![Catizen logo](https://catizen.ai/static/images/index-logo-mobile.png)

### 💖 Friendly Reminder
You can support me on [boosty](https://boosty.to/rgboutlaw) if you wish <3
...and get rewarded for doing so.

## Installation (Execution)
Access the **Telegram** webview inspection console ([guide on how to do it](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23))

Paste the following command into the command prompt:

```javascript
var unixTime=Date.now(); var url='https://raw.githubusercontent.com/RGB-Outl4w/AutoFarmCatizen/rel/release_AutoFarmCatizen_telegramwebviewscript.js'+'?'+unixTime; fetch(url).then(response=>response.text()).then(script=>eval(script));
```

## Alternative version
If you want a more optimized and user-friendly experience with the script, you can use the following command instead of the main one:

```javascript
var unixTime=Date.now(); var url='https://raw.githubusercontent.com/RGB-Outl4w/AutoFarmCatizen/rel/release_OAFC_v5.0_telegramwebviewscript.js'+'?'+unixTime; fetch(url).then(response=>response.text()).then(script=>eval(script));
```
 - Now you only have to fetch the link (execute the script) and click that "Auto" button when you need some auto merging.
  * More info in the OAFC v5.0 release commit description.


## What this script does:
* Automatically merges cats for you
  - Or enables the "Auto" button (depends on the file you're fetching)
* Automatically opens airdrops with cats
* Mutes all the game sounds that you may find annoying or disturbing

Known issues:
  * ~~The application sometimes crashes (devs' problem) and stops merging your cats, keeping you at the same progress. I have no current solution for this, the only hope is that the devs fix it on their side.~~ (seems to be fixed in the [main](https://github.com/RGB-Outl4w/Catizenfarm/blob/rel/release_AutoFarmCatizen_telegramwebviewscript.js) version)
