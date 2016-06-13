# Tasker Tasks [![GitHub forks](https://img.shields.io/github/forks/dudeofawesome/tasker-tasks.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/dudeofawesome/tasker-tasks#fork-destination-box)
A collection of my Tasker tasks that others might be interested in

## Task Descriptions

* [Play Music While Driving](/Play Music While Driving.xml)<a href="/Play Music While Driving.xml" style="margin-left: 10px;" download>![download](https://img.shields.io/badge/download-%20-brightgreen.svg)</a>
    * Starts music automatically when you get in your car
    * Set up to use Google Play Music by default, but can use most any service
    * Starts volume at 0 and ramps it up to ~85% over 5 seconds
    * Resets media volume to original volume after leaving the car

* <a href="/Play Music While Driving (Android Wear).xml">Play Music While Driving (with Android Wear watch with speaker)</a><a href="/Play Music While Driving (Android Wear).xml" style="margin-left: 10px;" download>![download](https://img.shields.io/badge/download-%20-brightgreen.svg)</a>
    * Works when you have an Android wear watch with a speaker
    * Starts music automatically when you get in your car
    * Set up to use Google Play Music by default, but can use most any service
    * Starts volume at 0 and ramps it up to ~85% over 5 seconds
    * Resets media volume to original volume after leaving the car

* [Sleep as Android](/Sleep as Android.xml)<a href="/Sleep as Android.xml" style="margin-left: 10px;" download>![download](https://img.shields.io/badge/download-%20-brightgreen.svg)</a>
    * Turns off lights and silences phone when sleep tracking is started
    * If you use music to fall asleep to, it will pause it after 30 minutes
    * Turns on your lights and unsilences when your alarm goes off
    * Turns your lights to 50% brightness if you snooze your alarm

## How to use

1. Install the [required apps](#required-apps) for the tasks you wish to use
1. Download the XML files onto your Android phone.
1. Open Tasker (Make sure you're not in Beginner Mode)
1. Long press on the project you want to import the task into
1. Select Import
1. Navigate through the file browser to the task's XML and open it
1. ??? (TODO: Actually follow the import instructions and make sure they work)
1. Follow the [task specific instructions](#task-specific-instructions) for each tasks you wish to use

### Task specific instructions

* Play Music While Driving
    1. Select the "Play Music While Driving" profile
    1. Set the Trigger to use your car's Bluetooth connection
    1. Open the "Play Music" task
    1. Open the 5th action and set the app you want it to play music from
* Play Music While Driving
    1. Select the "Play Music While Driving" profile
    1. Set the Trigger to use your car's Bluetooth connection
    1. Open the "Play Music" task
    1. Open the 5th action and set the app you want it to play music from
    1. Open the "Bluetooth Hack Connect" task
    1. Change the first Secure Settings action to disconnect from your watch
    1. Change the second Secure Settings action to disconnect from your car
    1. Change the third Secure Settings action to connect to your car
    1. Open the "Bluetooth Hack Disconnect" task
    1. Change the Secure Settings action to connect to your watch
* Sleep as Android
    1. There are no special instructions to follow


### Required apps
Task | Required Apps | |
-|-|-
Play Music While Driving | [<img src="https://lh3.googleusercontent.com/gdBHEk-u3YRDtuCU3iDTQ52nZd1t4GPmldYaT26Jh6EhXgp1mlhQiuLFl4eXDAXzDig5=w300-rw" style="margin-right: 5px;" height="24"> Google Play Music](https://play.google.com/store/apps/details?id=com.google.android.music) |
Play Music While Driving (With Wear) | [<img src="https://lh4.ggpht.com/lr2V4wwrZLPzxvAsR0OgwkZ1Ja8HXVRUes0N8fjlCVrKjfjtJK_WKkGYs6uFX0HKtk5M=w300-rw" style="margin-right: 5px;" height="24"> Secure Settings](https://play.google.com/store/apps/details?id=com.intangibleobject.securesettings.plugin) | [<img src="https://lh3.googleusercontent.com/gdBHEk-u3YRDtuCU3iDTQ52nZd1t4GPmldYaT26Jh6EhXgp1mlhQiuLFl4eXDAXzDig5=w300-rw" style="margin-right: 5px;" height="24"> Google Play Music](https://play.google.com/store/apps/details?id=com.google.android.music)
Sleep as Android | [<img src="https://lh3.googleusercontent.com/_d54j8d5ycmef4ldqkFbnfSXoqrBnvB9yIr8-yMszd-8fNa8UIsJAviNnhY4Vy0ugQ=w300-rw" style="margin-right: 5px;" height="24"> Sleep as Android](https://play.google.com/store/apps/details?id=com.urbandroid.sleep) | [<img src="https://lh6.ggpht.com/Ll27wlSaR_zCCwUFyjbEKlVxXgAk3-3WQwe0uwv61W9K3vOiGAJUaOX5pxkrBYTIdkDE=w300-rw" style="margin-right: 5px;" height="24"> Light Controller](https://play.google.com/store/apps/details?id=tv.piratemedia.lightcontroler)
