# Brightcove AppWidget Pending Intent Minimal Reproducible Example

Updating Brightcove broke opening the app from an app widget with TaskStackBuilder.
Opening the app shows an extra black task.

## Devices

Tested on:

- Pixel 7 Pro, Android 14
- Emulator, Android 13, x86_64

## Steps

* Install app
* Go to Android launcher
* Long tap -> widgets
* Place Brightcove Repro > Brightcove Repro widget
* Close all instances of the app in Recents
* Tap "Tap me" button on the widget
* Look at recents. There will be two Brightcove Repro tasks - first black, second with correct activity

Downgrading to 8.1.1 or removing the MainActivity from the TaskStackBuilder both 'fix' this issue.

![image](https://github.com/user-attachments/assets/83b7bfc1-4fc5-4045-88ee-8930b767058c)
