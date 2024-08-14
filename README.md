# Brightcove AppWidget Pending Intent Minimal Reproducible Example

Updating to Brightcove 8.4.4 broke opening the app from an app widget with TaskStackBuilder.
Opening the app shows an exact black task.
## Steps

* Install app
* Go to Android launcher
* Long tap -> widgets
* Place Brightcove Repro > Brightcove Repro widget
* Close all instances of the app in Recents
* Tap "Tap me" button.
* Look at recents. There will be two Brightcove Repro tasks - first black, second with correct activity

![image](https://github.com/user-attachments/assets/83b7bfc1-4fc5-4045-88ee-8930b767058c)
